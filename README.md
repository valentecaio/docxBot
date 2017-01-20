Description:
	That's a telegram bot who can read .docx files.

Content:
	This path should contain those files and subdirs:
		docx2txt.py		===> module to extract ASCII data from docx file
		docxbot.py		===> main bot module
		testFile.docx	===> a .docx file that can be used to test the bot
		temp/		====> a subdir to stock temporally files
		token.txt		===> a simple text file with a bot token

	IMPORTANT:
		If there's not token.txt, you should create one.
		The file shouldn't have spaces or line jumps. It might contain only your bot's token.
		To know more about this go to telegram bots documentation (https://core.telegram.org/bots#creating-a-new-bot)

How to execute bot:
	In a command line:
	> python docxbot.py