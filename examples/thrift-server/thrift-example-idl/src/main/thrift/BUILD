create_thrift_libraries(
  base_name='thrift',
  dependency_roots=[
    'finatra/thrift/src/main/thrift:thrift'
  ],
  sources=rglobs('*.thrift'),
  generate_languages=["java", "scala", "ruby", "python", "go"],
  provides_scala_name='calculator-thrift-scala'
)
