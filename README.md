You can read the original README.md file [here](https://github.com/CorentinJ/Real-Time-Voice-Cloning/blob/master/README.md)

After hours and hours of playing around and messing with package dependecy issues, I have finally managed to make it work in Conda environment.

Run ```python demo_cli.py``` and see if it works.

I'd suggest you to use conda virutal env.
Here is a [Google colab file](https://colab.research.google.com/drive/1s7SbRFFc-f88a2obYxWE_V6RZluKTNED?usp=sharing) which runs this repo and generates the audio output, as per task.

# Some Instructions and Suggestions

1. Please install all the packages 
```python
pip install -r requirements.txt
```
2. Make sure you have torch installed seperately (refer to original README file for more)
3. Make sure you have ffmpeg installed. ( not required for Google colab)
4. (Optional) If ```webrtcvad``` spits wheels error, try running this on CLI
```
pip install webrtcvad-wheels
```
