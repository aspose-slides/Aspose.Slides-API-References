---
title: Details_FileNotFoundException
second_title: Referencia de API de Aspose.Slides para C++
description: "La excepción que se lanza cuando se intenta acceder a un archivo que no existe en el disco. Nunca cree instancias de esta clase manualmente. Use la clase FileNotFoundException en su lugar. Nunca envuelva las instancias de la clase FileNotFoundException en System::SmartPtr."
type: docs
weight: 183
url: /es/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException clase


La excepción que se lanza cuando un intento de acceder a un archivo que no existe en el disco falla. Nunca cree instancias de esta clase manualmente. Use la clase FileNotFoundException en su lugar. Nunca envuelva las instancias de la clase FileNotFoundException en [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | Obtiene el nombre del archivo que causa esta excepción. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |
## Ver también

* Clase [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)