Description:
  Ping one or more hosts then act on up/down events with millisecond resolution

Usage:
  pingthen [options]

Options:
  -c, --config pingthen.conf
    Load pingthen.conf after trying /etc/pingthen.conf and ~/.pingthen.conf
  -h, --help
    Display this help message and exit.
  -v, --verbose #
    Use more or less verbose logging. Valid values are:
      0  No logging output.
      1  Log the start/stop of this script.
      2  Default. Log host state changes.
      3  Log the moving window results after each ping request.
      4  Log total results after each ping request.
      5  Log each function call with arguments.

Version:
  pingthen 5.0.2.0
  Copyright (C) 2013 Nathan Shearer
  Licensed under GNU General Public License 2.0
