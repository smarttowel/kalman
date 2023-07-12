project('kalman',
    default_options: ['warning_level=2',
                      'cpp_std=c++17',
                      'prefix=/usr'],
    version: '0.1.0',
    meson_version: '>=1.0.1')

eigen3_dep = dependency('eigen3')
kalman_dep = declare_dependency(compile_args: ['-DNDEBUG'],
                                dependencies: eigen3_dep,
                                include_directories: include_directories('include'))
