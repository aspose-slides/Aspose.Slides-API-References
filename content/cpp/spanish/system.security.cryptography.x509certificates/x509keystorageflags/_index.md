---
title: X509KeyStorageFlags
second_title: Referencia de API de Aspose.Slides para C++
description: Define cómo almacenar la clave.
type: docs
weight: 261
url: /es/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags enum


Define cómo almacenar la clave.

```cpp
enum class X509KeyStorageFlags : int32_t
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| DefaultKeySet | 0 | Usa el conjunto de claves predeterminado. |
| UserKeySet | 1 | Usa el almacén asociado al usuario en lugar del local de la máquina. |
| MachineKeySet | 2 | Usa el almacén local de la máquina en lugar del de usuario. |
| Exportable | 4 | Marca las claves importadas como exportables. |
| UserProtected | 8 | Notifica al usuario que la clave está siendo utilizada. |
| PersistKeySet | 16 | La clave se persiste al importar el certificado. |

## Ver también

* Espacio de nombres [System::Security::Cryptography::X509Certificates](../)
* Biblioteca [Aspose.Slides](../../)