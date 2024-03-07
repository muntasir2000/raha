<h1 align="center">Raha</h1>

<p align="center">
  <strong>A framework to enable multimodal models to operate a computer, and access any digital service. Ongoing development on making it available over a telephone call, so that people call via phone and avail digital services. It can be a plain old telephone call, without needing any smartphone, internet connection and the best thing is, the users don't need to know how to use the software. They can just speak and it will take care of what they want to do. </strong>
</p>
<p align="center">
  Using the same inputs and outputs as a human operator, the model views the screen and decides on a series of mouse and keyboard actions to reach an objective. 
</p>



## Demo


### Installation with `.sh`

1. **Clone the repo** to a directory on your computer:
```
git clone 
```
2. **Cd into directory**:

```
cd raha
```

3. **Run the installation script**: 

```
./run.sh
```

## Using `operate` 

**Cd into directory**:
```
cd raha
```
Install the additional `requirements-audio.txt`
```
pip install -r requirements-audio.txt
```
**Install device requirements**
For mac users:
```
brew install portaudio
```
For Linux users:
```
sudo apt install portaudio19-dev python3-pyaudio
```
Run with voice mode
```
operate --voice
```
