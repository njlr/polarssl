cxx_library(
  name = 'polarssl',
  header_namespace = 'polarssl',
  exported_headers = subdir_glob([
    ('include/polarssl', '*.h'),
  ]),
  srcs = glob([
    'library/*.c',
  ]),
  visibility = [
    'PUBLIC',
  ],
)
