shared_library(
  'zeitgeist-data-source-gala',
  'Main.vala',
  dependencies: [
    gala_dep,
    gee_dep,
    gio_unix_dep,
    glib_dep,
    gobject_dep,
    mutter_dep,
    zeitgeist_dep
  ],
  install: true,
  vala_args: vala_flags,
  c_args: c_flags,
  install_dir: plugins_dir,
  install_rpath: mutter_typelib_dir,
)
