all:

firefox:
	firefox *.xhtml

upload:
	rsync -a -v --progress dealing-with-trolls-summary.txt dealing-with-trolls-summary.xhtml $${HOMEPAGE_SSH_PATH}/trolls-cure-truk/
