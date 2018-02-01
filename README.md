# MirrorMirror

MirrorMirror is an exploration of one's perception of their image. It is a browser-enabled experience that provides an alternate reflection of yourself when you look back at the mirror.

<img width="1437" alt="first" src="https://cloud.githubusercontent.com/assets/22034616/25671191/0a62eb0a-2ffd-11e7-8648-f592ce99ee52.png">

Sense Me, Move Me is a class taught at ITP. The challenge was to design an interactive installation that moves you through space and time. I was interested in creating a piece that provoked the user to reflect and to question their sense of self.  Hence, I focused on the mirror as my object. Often when we look at mirrors, we see an image of ourselves that we want to see. So what if there was a mirror that disobeyed you? What if it could reveal parts of yourself you often don't show? 

I started by building my world using three.js, and a camera that would capture my user's face, distort it, and input it in room made of mirrors. I exaggerated the distortion in order to see how users would react when they are confronted with an image of themselves they are not used to seeing. My goal was to have users stop and truly reflect  by moving closer to the mirror. The closer they were, the faster the distortions.

Often we don't realize what we look like when we are angry, jealous or frustrated. My aim was to show that hidden side of ourselves . I arrayed these distortions in order to convey the sense of being trapped in a room full of infinite fractured images of ourselves. 

## How does it work?

MirrorMirror acts as an actual mirror. A user stops to look at their reflection whether it is to fix their hair, or check how they look. The mirror will then detect their face using a facial detection library, clmtrackr. Once a user's face is detected, their reflection is distorted and placed on the surfaces of  hundreds of spheres inside a mirrored room. As the user gets closer to the mirror to inspect what is happening, their reflection begins distorting faster and faster. 
