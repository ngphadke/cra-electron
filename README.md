# Background
My initial attempt to get React working inside electron is documented in my [react-electron-starter](https://github.com/ngphadke/react-electron-starter) repo.
This was under the understanding that getting Electron working in a CRA-based React while using node modules that run outside of a browser runtime was not possible. Not unless someone had the guts to eject the CRA app.

More research showed that there was an easy and understandable way to get this done.

# Thanks
Many thanks to @msanatan for his brilliant piece on how to get this working. Found [here](https://msanatan.com/2020/04/19/accessing-nodejs-modules-with-create-react-app-and-electron/).