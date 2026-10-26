---
title: GetCompareInfo()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene CompareInfo asociado con la cultura especificada y utilizando los métodos de comparación de cadenas en el ensamblado especificado.
type: docs
weight: 183
url: /es/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) método


Obtiene [CompareInfo](../) asociado con la cultura especificada y usando los métodos de comparación de cadenas en el ensamblado especificado.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| culture | int | Identificador de cultura (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Ensamblado que contiene los métodos de comparación de cadenas. |

### Valor devuelto

[CompareInfo](../) objeto.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) método


Obtiene [CompareInfo](../) asociado con la cultura especificada y usando los métodos de comparación de cadenas en el ensamblado especificado.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nombre de la cultura. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Ensamblado que contiene los métodos de comparación de cadenas. |

### Valor devuelto

[CompareInfo](../) objeto.

## CompareInfo::GetCompareInfo(int) método


Obtiene [CompareInfo](../) asociado con la cultura especificada.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| culture | int | Identificador de cultura (LCID). |

### Valor devuelto

[CompareInfo](../) objeto.

## CompareInfo::GetCompareInfo(const String\&) método


Obtiene [CompareInfo](../) asociado con la cultura especificada.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nombre de la cultura. |

### Valor devuelto

[CompareInfo](../) objeto.

## Ver también

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Assembly](../../../system.reflection/assembly/)
* Clase [CompareInfo](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Globalization](../../)
* Biblioteca [Aspose.Slides](../../../)