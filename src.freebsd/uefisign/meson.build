uefisign_prog = executable(
    'uefisign',
    [ 'child.c', 'pe.c', 'uefisign.c' ],
    include_directories : [ inc ],
    link_with : [ libcompat ],
    dependencies : [ libcrypto ],
    install : true,
)

install_man('uefisign.8')
