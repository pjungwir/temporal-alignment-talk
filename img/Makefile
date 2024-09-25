all: reservations.svg reservations_joined.svg products_rows.png products_timeline.png products_rows_ranges.png splitter.svg aligner.svg

%.png: %.txt
	ditaa -o -E $<

%.svg: %.mermaid
	# npm install -g @mermaid-js/mermaid-cli
	mmdc -i $< -o $@

.PHONY: all
