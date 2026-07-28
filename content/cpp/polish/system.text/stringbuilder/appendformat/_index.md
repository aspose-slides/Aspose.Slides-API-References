---
title: AppendFormat()
second_title: Aspose.Slides dla C++ - referencja API
description: Dodaje sformatowany ciąg znaków do buildera.
type: docs
weight: 131
url: /pl/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String\&, const TArgs\&...) metoda


Dodaje sformatowany ciąg znaków do buildera.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TArgs | Typ argumentów. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Łańcuch formatu. |
| args | const TArgs\&... | Argumenty do wstawienia w pozycje ciągu formatu. |

### Wartość zwracana

Ten wskaźnik.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) metoda


Dodaje sformatowany ciąg znaków do buildera.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TArgs | Typ argumentów. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | Dostawca formatu; ignorowany. |
| format | const [String](../../../system/string/)\& | Łańcuch formatu. |
| args | const TArgs\&... | Argumenty do wstawienia w pozycje ciągu formatu. |

### Wartość zwracana

Ten wskaźnik.

## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [StringBuilder](../)
* Klasa [String](../../../system/string/)
* Klasa [IFormatProvider](../../../system/iformatprovider/)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)