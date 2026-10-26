---
title: GetCultureInfo()
second_title: Aspose.Slides para C++ - Referência da API
description: Obtém a cultura pelo seu nome. Equivalente a CreateSpecificCulture.
type: docs
weight: 586
url: /pt/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) método


Obtém a cultura pelo seu nome. Equivalente a CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nome de cultura predefinido ou nome de um objeto de cultura existente. |

### Valor de Retorno

Objeto de cultura recém-criado.

## CultureInfo::GetCultureInfo(const String\&, const String\&) método


Obtém a cultura pelo seu nome.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nome da cultura. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | Nome da cultura usado para objetos [TextInfo](../../textinfo/) e [CompareInfo](../../compareinfo/). |

### Valor de Retorno

Objeto de cultura.

## CultureInfo::GetCultureInfo(int32_t) método


Obtém a cultura por ID.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| culture | **int32_t** | Identificador da cultura. |

### Valor de Retorno

Objeto de cultura recém-criado.

## Veja Também

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Classe [String](../../../system/string/)
* Classe [CultureInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)