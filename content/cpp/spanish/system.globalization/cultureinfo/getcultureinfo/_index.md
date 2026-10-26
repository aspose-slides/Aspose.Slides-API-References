---
title: GetCultureInfo()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene la cultura por su nombre. Igual que CreateSpecificCulture.
type: docs
weight: 586
url: /es/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) método


Obtiene la cultura por su nombre. Igual que CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nombre de cultura predefinido o nombre del objeto de cultura existente. |

### Valor devuelto

Objeto de cultura recién creado.

## CultureInfo::GetCultureInfo(const String\&, const String\&) método


Obtiene la cultura por su nombre.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nombre de la cultura. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | Nombre de cultura utilizado para los objetos [TextInfo](../../textinfo/) y [CompareInfo](../../compareinfo/). |

### Valor devuelto

Objeto de cultura.

## CultureInfo::GetCultureInfo(int32_t) método


Obtiene la cultura por id.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| culture | **int32_t** | Identificador de cultura. |

### Valor devuelto

Objeto de cultura recién creado.

## Ver también

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Clase [String](../../../system/string/)
* Clase [CultureInfo](../)
* Espacio de nombres [System::Globalization](../../)
* Library [Aspose.Slides](../../../)