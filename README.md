Schwab OAuth return page for https://rava8989.github.io/brave/ (the address registered with the Schwab app).
It only forwards Schwab's ?code=…&state=… to the signal worker's /oauth-callback, which checks the state and finishes the login. No secrets live here.
