Blog post for the aritcle: https://paulihuhtiniemi.com/blog/2019/07/03/masters-thesis-markdown 
Thesis template in Markdown, uses [LUT University guidelines](https://uni.lut.fi/en/web/lut.fi-eng/master-s-thesis-project4). Adapted from https://github.com/tompollard/phd_thesis_markdown by Tom Pollard, head over to original repository for more information on how this template is organized and what requirements there are.

You may view example of generated PDF in `output/thesis.pdf`.

I have quite limited understanding on LaTeX, so there are most likely definitions and hacks that could be done better. If something breaks, you may keep all the pieces.

# Requirements

You will need tools like [Pandoc](https://pandoc.org/), please see the original [repository](https://github.com/tompollard/phd_thesis_markdown) for more information.

# Instructions:

Update HTML version automatically:

    npm run watch

Generate PDF:

    make pdf
