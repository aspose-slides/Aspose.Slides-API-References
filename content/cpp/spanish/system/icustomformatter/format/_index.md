---
title: Format()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una representación de cadena de un valor representado por el objeto actual usando el formato especificado.
type: docs
weight: 1
url: /es/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) método

Devuelve una representación de cadena de un valor representado por el objeto actual usando el formato especificado.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | [System::String](../../string/) | El formato de cadena |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | El objeto a formatear |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | El objeto que proporciona la información de formato |

### Valor devuelto

La representación de cadena de **arg** formateada según el formato especificado por **format** y **formatProvider**

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [Object](../../object/)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [ICustomFormatter](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)