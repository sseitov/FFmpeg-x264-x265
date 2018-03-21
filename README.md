# FFmpeg-x264-x265

1) ./build-x264.sh
2) ./build-fdk-aac.sh
3) build x256foriOS/x265foriOS.xcodeproj
4) create universal library x265.a from result
5) move x265.a to x256foriOS/lib/
6) edit prefix in x265.pc
7) ./build-ffmpeg
