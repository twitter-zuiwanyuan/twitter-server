# test twitter-server

junit_tests(name='scala',
  dependencies=[
    'finagle/finagle-toggle',
    'twitter-server/src/test:base',
    'twitter-server/src/main/scala'
  ],
  fatal_warnings=True,
  sources=rglobs('*.scala'),
  resources=['twitter-server/src/test/resources']
)
