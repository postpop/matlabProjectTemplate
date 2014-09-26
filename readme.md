prj.subprj/
	dat (contains raw data files)
	doc (descpriptions, notes, presentations posters)
	fig (plots)
	log (contains script output)
	pub (paper (drafts))
	res (for caching intermediate results that take a long time)
	src (all the code)
    web (a website for hosting the code???)
	Makefile (main file calling all subroutines in src??)
	readme.md (short description of the project and associated files)
	todo.md (guess what?)

explain what each folder is supposed to contain
inspired by:
	[projecttemplate](http://projecttemplate.net/gettingstarted.html)
	[workflow by rh](http://robjhyndman.com/hyndsight/workflow-in-r/)
	[makefile by rh](http://robjhyndman.com/hyndsight/makefiles/)
    [post on stackoverflow](http://stackoverflow.com/questions/1429907/workflow-for-statistical-analysis-and-report-writing)
	[kbromans minimal make tutorial](http://kbroman.org/minimalmake/)
	
- each script creates outputs (files in RES and FIG) that have its name plus some optional suffix 
- account for serialization
- check for cached files (could use make for this)