---
title: AppendFormat()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přidá formátovaný řetězec do builderu.
type: docs
weight: 131
url: /cs/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String\&, const TArgs\&...) metoda


Přidá formátovaný řetězec do builderu.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TArgs | Typ argumentů. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Formátovací řetězec. |
| args | const TArgs\&... | Argumenty k vložení na pozice formátovacího řetězce. |

### Návratová hodnota

Tento ukazatel.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) metoda


Přidá formátovaný řetězec do builderu.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TArgs | Typ argumentů. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | Poskytovatel formátu; ignorováno. |
| format | const [String](../../../system/string/)\& | Formátovací řetězec. |
| args | const TArgs\&... | Argumenty k vložení na pozice formátovacího řetězce. |

### Návratová hodnota

Tento ukazatel.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [StringBuilder](../)
* Třída [String](../../../system/string/)
* Třída [IFormatProvider](../../../system/iformatprovider/)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)