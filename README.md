This repo contains a `settings.xml` file that can be used to deploy snapshots to SonaType from a
Travis CI build. The full instructions are here:

http://blog.xeiam.com/blog/2013/05/10/configure-travis-ci-to-deploy-snapshots/

That article recommends putting these settings in a branch in your project, but having it in a new
project avoids cloning your entire (possibly large) Git repo just for one settings file.
