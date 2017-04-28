# resume_projPYTHON-RESUME-BUILDER

This project uses a python template system to produce many output formats of the same resume. The resume is stored directly in python source code and pushed through the jinja template system (similar to Django) to plain text, html and tex source. The tex source can then be compiled to PDF using pdflatex.

REQUIREMENTS

*nix (tested with Debian Wheezy)
Python (tested with 2.7.3)
Jinja (tested with 2.6, via debian package python-jinja2)
pdflatex (tested with debian package texlive-full)
a LOT of LaTeX packages. (tested with the 2GB+ texlive-full package, rather than grabbing individual libraries)
INSTRUCTIONS

From the project directory, run:

~$ ./build_resume.py [source_file.py]
~$ pdf_latex [source_file.tex]

TO-DO

Update main script to validate arguments
Add usage statement to main script
change resume source_file format to a friendlier format than .py.
add octocat icon next to github url!
