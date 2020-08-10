# DOMPDF-chinese-font-issue-solved
How to solve dompdf chinese unicode problems

1. Download the simhei font to a desired location
2. Use load_font.php, (utils project) download from here
3. After loading font into dompdf fonts dir using load_font.php
4. set font-family:simhei;
5. enjoy!!!

commands------------------------

php /path/load_font.php simhei /path/simhei.ttf

reproduce----------------------------
Unable to find bold face file.
Unable to find italic face file.
Unable to find bold_italic face file.
Copying /home/potential/simhei.ttf to /home/judge/jnoj/web/report_wizard/vendor_dompdf/dompdf/dompdf/lib/fonts/simhei.ttf...
Generating Adobe Font Metrics for /home/judge/jnoj/web/report_wizard/vendor_dompdf/dompdf/dompdf/lib/fonts/simhei...


Done!
the load_font.php will load the requered font files and update font_family_cache.php
