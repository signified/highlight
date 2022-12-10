STYLES = base16
STYLES += base16.dark
STYLES += base16.light
STYLES += base16.monokai
STYLES += base16.monokai.dark
STYLES += base16.monokai.light
STYLES += base16.solarized
STYLES += base16.solarized.dark
STYLES += base16.solarized.light
STYLES += bw
STYLES += colorful
STYLES += github
STYLES += gruvbox
STYLES += gruvbox.dark
STYLES += gruvbox.light
STYLES += igorpro
STYLES += magritte
STYLES += molokai
STYLES += monokai
STYLES += monokai.sublime
STYLES += pastie
STYLES += thankful_eyes
STYLES += tulip

rougify = rougify style $(style) > css/$(style).css;

cssfiles:
	@$(foreach style, $(STYLES), $(rougify))
