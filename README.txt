
Unpack the libraries API into your Drupal 7 modules directory

Unpack the ArbiterJS module into your Drupal 7 modules directory

Unpack the jssip module into your Drupal 7 modules directory

Unpack this jscommunicator module into your Drupal 7 modules directory

Relative to the Drupal home,
  mkdir -p sites/all/libraries/jscommunicator

Download JSComm.js from http://jscommunicator.org/download into
  sites/all/libraries/jscommunicator

Create the VERSION file:

echo "1.0.1" > sites/all/libraries/jscommunicator/VERSION

Now log in to Drupal, go to the Modules administration page and
enable the modules:

  * libraries
  * arbiterjs
  * jssip
  * jscommunicator

Finally, install and enable any other modules that want to use JSCommunicator
such as DruCall.


