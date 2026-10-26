---
title: CipherMode
second_title: Referencia de la API de Aspose.Slides para C++
description: Modo de cifrado por bloques.
type: docs
weight: 885
url: /es/system.security.cryptography/ciphermode/
---
## CipherMode enumeración

Modo de cifrado por bloques.

```cpp
enum class CipherMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| CBC | 1 | Encadenamiento de bloques de cifrado que combina el bloque actual con el bloque anterior para mejorar el cifrado. |
| ECB | 2 | Modo de libro de códigos electrónico sin influencias entre bloques; resulta en un cifrado más débil. |
| OFB | 3 | Modo de retroalimentación de salida que maneja bloques de entrada grandes en piezas pequeñas. |
| CFB | 4 | Modo de retroalimentación de cifrado que maneja bloques de entrada grandes en piezas pequeñas. Las reglas de alteración difieren de las de OFB. |
| CTS | 5 | Modo de robo de texto cifrado, se comporta como CBC para todos excepto los dos últimos bloques de texto. |

## Ver también

* Espacio de nombres [System::Security::Cryptography](../)
* Biblioteca [Aspose.Slides](../../)