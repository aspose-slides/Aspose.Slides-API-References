---
title: CompareDocument()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Gdy zostanie przesłonięta w klasie pochodnej, porównuje podstawowe identyfikatory Uniform Resource Identifier (URI) dwóch dokumentów na podstawie kolejności, w której dokumenty zostały wczytane przez procesor XSLT (to jest klasa XslTransform).
type: docs
weight: 53
url: /pl/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) metoda


Gdy zostanie przesłonięta w klasie pochodnej, porównuje podstawowe Uniform Resource Identifiers (URI) dwóch dokumentów na podstawie kolejności, w której dokumenty zostały wczytane przez procesor XSLT (to jest klasa [XslTransform](../../xsltransform/)).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | Podstawowy URI pierwszego dokumentu do porównania. |
| nextbaseUri | [String](../../../system/string/) | Podstawowy URI drugiego dokumentu do porównania. |

### Wartość zwracana

Liczba całkowita opisująca względny porządek dwóch podstawowych URI: -1 jeśli **baseUri** występuje przed **nextbaseUri**; 0 jeśli oba podstawowe URI są identyczne; oraz 1 jeśli **baseUri** występuje po **nextbaseUri**.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XsltContext](../)
* Przestrzeń nazw [System::Xml::Xsl](../../)
* Biblioteka [Aspose.Slides](../../../)