---
title: GetCompareInfo()
second_title: Referência da API Aspose.Slides para C++
description: Obtém CompareInfo associado à cultura especificada e usando métodos de comparação de strings no assembly especificado.
type: docs
weight: 183
url: /pt/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) método


Obtém [CompareInfo](../) associado à cultura especificada e usando métodos de comparação de strings no assembly especificado.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| culture | int | Identificador de cultura (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly que contém métodos de comparação de strings. |

### Valor de retorno

[CompareInfo](../) objeto.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) método


Obtém [CompareInfo](../) associado à cultura especificada e usando métodos de comparação de strings no assembly especificado.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nome da cultura. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly que contém métodos de comparação de strings. |

### Valor de retorno

[CompareInfo](../) objeto.

## CompareInfo::GetCompareInfo(int) método


Obtém [CompareInfo](../) associado à cultura especificada.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| culture | int | Identificador de cultura (LCID). |

### Valor de retorno

[CompareInfo](../) objeto.

## CompareInfo::GetCompareInfo(const String\&) método


Obtém [CompareInfo](../) associado à cultura especificada.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nome da cultura. |

### Valor de retorno

[CompareInfo](../) objeto.

## Veja também

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Assembly](../../../system.reflection/assembly/)
* Classe [CompareInfo](../)
* Classe [String](../../../system/string/)
* Namespace [System::Globalization](../../)
* Biblioteca [Aspose.Slides](../../../)