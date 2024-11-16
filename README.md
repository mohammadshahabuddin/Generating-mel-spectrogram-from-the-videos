# Generating-mel-spectrogram-from-the-videos:Convert Video Audio to Mel-Spectrogram Images

This repository features a Python script that extracts audio from video files and converts it into high-quality Mel-spectrogram images. Using Librosa for audio processing and Matplotlib for visualization, this tool is ideal for creating datasets or visualizing audio features for video-based projects.

# Features
1. Video Processing: Extracts audio from video files in .mp4 format.

2. Mel-Spectrogram Generation:

Converts extracted audio signals to Mel-spectrograms.

Scales power values to decibels for better visualization.

3. Image Output: Saves the spectrograms as transparent .jpg images, ready for integration into datasets or analysis workflows.

4. Batch Processing: Automatically processes multiple video files in a folder.

# Workflow
1. Input Videos: Provide a folder containing .mp4 video files.

2. Audio Extraction and Processing:

Extracts audio from each video.

Generates Mel-spectrograms from the audio signal.

3. Image Output: Saves each Mel-spectrogram as a .jpg image in the specified output folder.
# Applications
Preparing labeled datasets for audio or video machine learning models.

Analyzing audio features extracted from videos.

Generating visual representations for audio debugging or presentations.

# Requirements
Python

Librosa

Matplotlib

NumPy
