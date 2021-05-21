# Not Geoff

This repo contains most of the source code (exclusing the resnet training script) for the CS 125 project "Not Geoff", a PWA image classifier made my Ajay Uppili Arasanipalai (NetID: aua2) and Richwell Perez (NetID: richwell).

The app is deployed on a cloud service called [Render](https://render.com/). Due to limitations on the free tier, the app may not remain live at the url https://not-geoff.onrender.com/static/index.html. If you would like to depoly the app youself, simply create an account on Render, clone this repo, and direct Render to build the app from your repo code.

The important source code can be found under the `app/static` directory. This is what is served from render. The backend code can be found at `app/server.py`.

The neural net was trained using [fastai](https://docs.fast.ai/). We do not plan to release the training script at this time.
