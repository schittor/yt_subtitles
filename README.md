# yt_subtitles
YouTube subtitles : Programs to generate subtitles for videos assembled from many small cips.

yt_subtitles.exe : The programs were developed for VSK Portland and copyright by VSK portland, but can be used for any non-profit purpose.
yt_subtitles.exe is a windows desktop executable (written in C source) that can generate YouTube subtitles for the final video from a 
human-friendly input per-clip grouped subtitles file that gives incremental timings for each subtitle within the clip. It can also do other things such as 
tags subtitles with character tags, reverse translate from YouTube subtitles file into a per-clip grouped subtitle.

yt_subtitles.py : A python program that supplements yt_subtitles.exe by supporting two-level structure, video sectios and video clips with it. 
Program generates flattened 1-level input file for yt_subtitles.exe. 

yt_subtitles.docs : User manual for yt_subtitles.exe.

Plan to add user manual for yt_subtitle.exe

Sample files :

rk1_subtitles.txt : Input file to yt_subtitles.exe.

rk1_subtitles_timings.txt : Output of yt_subtitles.exe.

rk1_subtitles_sections_details.txt : Log file generated by yt_subtitles.exe giving 1-line subtitle summary of video clips.

rk1_clip_start.txt : Additional optional file that can help with alignment, can be input or output from yt_subtitles.exe.

rk_subtitles.txt : Input file to yt_subtitles.py that will generate rk1_subtitles.txt
