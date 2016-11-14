# Weaving reproducibility through the undergraduate statistics curriculum

This repository contains slides for and any additional resources related to the "Integrating reproducibility into the undergraduate statistics curriculum" talk as part of the ASA Webinar titled [Teaching Reproducible Research: Inspiring New Researchers to do More Robust and Reliable Science](http://www.amstat.org/ASA/Education/Web-Based-Lectures.aspx#TRR) on Wednesday, November 16, 2016, 2:30 p.m. - 3:30 p.m.

## Description

With recent emphasis on robust and reliable science, a minimal standard for data analysis and other scientific computations is that they be reproducible—that the code and data are assembled in a way that all the results can be re-created (e.g., the figures in a paper). While adopting a workflow that will make results reproducible will ultimately make a researcher’s life easier, this goal will not be easy to achieve without the right tools and organization.

In this webinar, three reproducible research experts share how they teach undergraduate and graduate students to make their research reproducible. They recommend instilling best practices in students as early as possible and teaching data analysis at all levels of a science curriculum using a completely reproducible framework. In this way, new researchers will know no other workflow than a reproducible one. They also urge statisticians to marshal efforts to promote reproducible data analysis practices in other disciplines. While all this might sound like a tall order at first, modern tools for literate programming (e.g., R Markdown) and systems for version control (e.g., GitHub, Open Science Framework) paired with carefully designed curricula make this goal easier to attain than ever before.


## Talk outline

- Intro:
	- Two pronged approach to spreading reproducibility:
		+ Convince researchers to change their workflows and adopt reproducible ones
		+ Train new researchers who have no other workflow -- this talk focused on this prong
	- Research / teaching:
		+ Often comes up in the context of published research and the need to accompany such research with the complete data and analyses, including software/code 
		+ Educators who teach data analysis should be instilling best practices in students before they set out to do research
- Share experiences from undergraduate courses that teach data analysis within a reproducibile framework
	+ Intro stat 
		- Toolkit: R + RStudio + R Markdown
		- Address common concern: Can students handle it? Oh yeah! 
			+ Scripting vs. GUI
			+ Scripting + RR tools: In fact, this workflow makes it easier to learn R since 
				- keeps workspace clean, 
				- keeps code organized, 
				- code + output always together, and 
				- syntax highlighting
		- More course info: 
			- Course website: https://www.stat.duke.edu/courses/Spring16/sta101.001/
			- Course materials: https://github.com/mine-cetinkaya-rundel/sta101-s16
	+ Intro data science 
		- Toolkit: R + RStudio + R Markdown + git + Github
		- Address common concern: Can students handle it? Yes, 
			+ But need to make instruction of workflow part of the curriculum 
			- Can't just hope students will figure it out
		- More course info: 
			- Course website: https://www.stat.duke.edu/courses/Fall15/sta112.01/
			- Course materials: https://github.com/mine-cetinkaya-rundel/sta112_f15
	+ Advanced stat computing 
		- Toolkit: R + RStudio + R Markdown + git + Github + Testing / Continuous Integration
		- More info at http://bit.ly/statcomp_jsm2016
		- Lesson: grow toolkit along with the complexity of computation
		- Materials: 
			- Course website: http://www.stat.duke.edu/~cr173/Sta323_Sp16/
			- Course materials: https://github.com/Sta323-Sp16
- 2016/2017 projects: Carry the theme of reproducibility through the entire major with a capstone course and senior thesis that is fully reproducible
	+ Need instructor buy-in
	+ Needs to be part of the assessment
	+ Easily adoptable workflow helps
		- [Karl's Steps 2 RR](http://kbroman.org/steps2rr/)
		- [Project TIER](https://www.haverford.edu/tier) protocol
		- [Reproducible Science Curriculum](https://github.com/Reproducible-Science-Curriculum)
- More comments on toolkit:
	+ R / RStudio: Recommended
	+ But R not necessary: 
		- Any scripting language might work 
		- Even though the overhead in some might be more than others
- Pleasant side-effects:
	+ For instructor: easy Q&A + easy grading
	+ For student: easy collaboration + self promotion# 2016-11-14-reproducible-undergrad-stats
