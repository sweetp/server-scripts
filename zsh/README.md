This scripts are little helpers to save some typing. To use the functions
provided in the directory 'functions' in here you must copy the functions dir
into ~/.zsh. Additionally you must add this to your ~/.zshrc

	fpath=(~/.zsh/functions $fpath)
	autoload -U ~/.zsh/functions/*(:t)
