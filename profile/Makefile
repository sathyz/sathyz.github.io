all: html

html: profile.md style.css
	pandoc --standalone -c style.css --from markdown --to html -o index.html profile.md

clean:
	rm -rv index.html
