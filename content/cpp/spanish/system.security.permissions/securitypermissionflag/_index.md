---
title: SecurityPermissionFlag
second_title: Referencia de API de Aspose.Slides para C++
description: Banderas de permiso de seguridad.
type: docs
weight: 27
url: /es/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum

Banderas de permiso de seguridad.

```cpp
enum class SecurityPermissionFlag
```

### Values

| Nombre | Valor | Descripción |
| --- | --- | --- |
| NoFlags | 0 | Sin acceso. |
| Assertion | 1 | Afirmar que el permiso está concedido. |
| UnmanagedCode | 2 | Llamar a código no administrado. |
| SkipVerification | 4 | Omitir la verificación del código. |
| Execution | 8 | Ejecutar código. |
| ControlThread | 16 | Realizar operaciones sobre hilos. |
| ControlEvidence | 32 | Controlar o modificar la evidencia del CLR. |
| ControlPolicy | 64 | Ver y cambiar la política. |
| SerializationFormatter | 128 | Serializar. |
| ControlDomainPolicy | 256 | Establecer la política del dominio. |
| ControlPrincipal | 512 | Controlar el objeto principal. |
| ControlAppDomain | 1024 | Controlar el dominio de la aplicación. |
| RemotingConfiguration | 2048 | Configurar la comunicación remota. |
| Infrastructure | 4096 | Conectarse a la infraestructura CLR. |
| BindingRedirects | 8192 | Realizar redirección explícita de enlace. |
| AllFlags | 16383 | Sin restricciones. |

## Ver también

* Espacio de nombres [System::Security::Permissions](../)
* Biblioteca [Aspose.Slides](../../)