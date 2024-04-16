# Input RTP dumps

- `8_colors_input.mp4`
    - 8 images where each image appears for 2 seconds. Every image is a checkerboard with a border and different primary color. Together with the images, an audio is played. Every 2 seconds a different sinewave frequency is played.
    - Resolution: 640x360
    - Duration: 16 seconds
    - Video codec: h264
    - Audio codec: Opus
    - RTP dumps:
        - `8_colors_input_video.rtp` - only video
        - `8_colors_input_audio.rtp` - only audio
        - `8_colors_input_video_audio.rtp` - video and audio muxed together

- `8_colors_input_reversed.mp4`
    - Same as `8_colors_input.mp4` but the images and audio are played in reverse order.
    - Resolution: 640x360
    - Duration: 16 seconds
    - Video codec: h264
    - Audio codec: Opus
    - RTP dumps:
        - `8_colors_input_reversed_video.rtp` - only video
        - `8_colors_input_reversed_audio.rtp` - only audio

- `8_colors_long_input.mp4`
    - `8_colors_input.mp4` repeated 4 times.
    - Resolution: 640x360
    - Duration: 1 minute and 20 seconds
    - Video codec: h264
    - Audio codec: Opus
    - RTP dumps:
        - `8_colors_long_input_video.rtp` - only video

- `countdown.mp4`
    - Audio of a man counting down from 10 to 1.
    - Duration: 16 seconds
    - Audio codec: Opus
    - RTP dumps:
        - `countdown_audio.rtp` - only audio

- `big_buck_bunny_10s.mp4`
    - The first 10 seconds of the Big Buck Bunny movie
    - Resolution: 1280x720
    - Duration: 10 seconds
    - Video codec: h264
    - Audio codec: AAC
    - RTP dumps:
        - `big_buck_bunny_10s_audio_aac.rtp` - only audio
