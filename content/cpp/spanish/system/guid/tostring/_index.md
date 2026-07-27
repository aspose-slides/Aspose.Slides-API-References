---
title: ToString()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el GUID representado por el objeto actual a su representación en forma de cadena.
type: docs
weight: 79
url: /es/system/guid/tostring/
---
## Guid::ToString() const método


Convierte el GUID representado por el objeto actual a su representación en forma de cadena.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const método


Convierte el GUID representado por el objeto actual a su representación en forma de cadena usando el formato de cadena especificado.

```cpp
String System::Guid::ToString(const String &format) const
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | const [String](../../string/)\& | El formato a usar |

### Valor devuelto

La representación en forma de cadena del valor GUID representado por el objeto actual

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const método


Convierte el GUID representado por el objeto actual a su representación en forma de cadena usando el formato de cadena especificado y la Cultura.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | const [String](../../string/)\& | El formato a usar |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a usar |

### Valor devuelto

La representación en forma de cadena del valor GUID representado por el objeto actual

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [Guid](../)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)