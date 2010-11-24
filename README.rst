Installation::

    python bootstrap.py
    ./bin/buildout
    ./bin/develop co .*
    ./bin/buildout
    cp store/local_settings.py.default store/local_settings.py
    ./bin/django syncdb
    ./bin/django satchmo_load_l10n
    ./bin/django satchmo_load_store
    ./bin/django satchmo_rebuild_pricing
