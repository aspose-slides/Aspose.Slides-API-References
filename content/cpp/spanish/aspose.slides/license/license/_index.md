---
title: License()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inicializa una nueva instancia de esta clase.
type: docs
weight: 1
url: /es/aspose.slides/license/license/
---
## License::License() constructor

Inicializa una nueva instancia de esta clase.

```cpp
Aspose::Slides::License::License()
```

## Observaciones

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado llamador, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado llamador. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## Ver también

* Clase [License](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)