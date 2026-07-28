---
title: idx_get()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Po nadpisaniu w klasie pochodnej, pobiera wartość atrybutu o określonym indeksie.
type: docs
weight: 612
url: /pl/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) metoda

Po nadpisaniu w klasie pochodnej, pobiera wartość atrybutu o podanym indeksie.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| i | **int32_t** | Indeks atrybutu. |

### Wartość zwracana

Wartość określonego atrybutu.

## XmlReader::idx_get(String) metoda

Po nadpisaniu w klasie pochodnej, pobiera wartość atrybutu o określonej wartości [XmlReader::get_Name](../get_name/).

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | W pełni kwalifikowana nazwa atrybutu. |

### Wartość zwracana

Wartość określonego atrybutu. Jeśli atrybut nie zostanie znaleziony, zwracane jest **nullptr**.

## XmlReader::idx_get(String, String) metoda

Po nadpisaniu w klasie pochodnej, pobiera wartość atrybutu o określonych wartościach [XmlReader::get_LocalName](../get_localname/) i [XmlReader::get_NamespaceURI](../get_namespaceuri/).

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Lokalna nazwa atrybutu. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw atrybutu. |

### Wartość zwracana

Wartość określonego atrybutu. Jeśli atrybut nie zostanie znaleziony, zwracane jest **nullptr**.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)