# kazoo-regextern
external number of providers integration in kazoo

this is for internal use only, to integration with telecom services

1. INSTALL kazoo-platform
2. INSTALL monster-ui (from this repository because of adds in ui)
3. INSTALL THIS in a subfolder where one of kazoo-freeswitch is AND ADD php-cli with fping support there
    - config first your couchdb and node settings in $hosts = "" on config.php
    - kazoo-addon move this file  to init.d to start as service
4. FOLLOW the instruction on 2600hz-dev on google-groups to allow ONLY! calls from your providers

If you have more ideas let me known on this github repository

