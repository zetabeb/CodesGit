fatal: unable to access 'https://github.com/perfil/Repositorio.git/': error setting certificate verify locations:
  CAfile: C:/Archivos de programa/Git/mingw32/libexec/ssl/certs/ca-bundle.crt
  CApath: none

solución: git config --global http.sslverify "false"
(no recomendado, pero puede ser una solucón para XP)

para desactivar TLS/SSL, en caso para problemas de permisos denegados
git -c http.sslVerify=false
