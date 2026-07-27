---
title: XmlKnownDtds
second_title: Referencia de la API de Aspose.Slides para C++
description: "La enumeración Resolvers::XmlKnownDtds es utilizada por Resolvers::XmlPreloadedResolver y define qué DTDs bien conocidos reconoce Resolvers::XmlPreloadedResolver."
type: docs
weight: 14
url: /es/system.xml.resolvers/xmlknowndtds/
---
## XmlKnownDtds enum

La enumeración [Resolvers::XmlKnownDtds](./) es utilizada por [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) y define qué DTDs bien conocidos reconoce [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/).

```cpp
enum class XmlKnownDtds
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 | Especifica que [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) no reconocerá ninguno de los DTDs predefinidos. |
| Xhtml10 | 1 | Especifica que [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) reconocerá DTDs y entidades que están definidas en XHTML 1.0. |
| Rss091 | 2 | Especifica que [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) reconocerá DTDs y entidades que están definidas en RSS 0.91. |
| All | 65535 | Especifica que [Resolvers::XmlPreloadedResolver](../xmlpreloadedresolver/) reconocerá todos los DTDs actualmente compatibles. Este es el comportamiento predeterminado. |

## Ver también

* Espacio de nombres [System::Xml::Resolvers](../)
* Biblioteca [Aspose.Slides](../../)