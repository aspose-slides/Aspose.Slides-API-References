---
title: set_license method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
Licensierar komponenten.

```python
def set_license(self, license_name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| license_name | **str** | Kan vara ett fullständigt eller förkortat filnamn eller namnet på en inbäddad resurs.<br/><br/> Använd en tom sträng för att byta till utvärderingsläge. |

### Anmärkningar

Försöker hitta licensen på följande platser:

1. Explicit sökväg.
2. Mappen för komponentens assembly.
3. Mappen för klientens anropande assembly.
4. Mappen för entry assembly.
5. En inbäddad resurs i klientens anropande assembly.

**Obs:** På .NET Compact Framework försöker endast hitta licensen på dessa platser:

1. Explicit sökväg.
2. En inbäddad resurs i klientens anropande assembly.

## set_license(self, stream) {#iorawiobase}
Licensierar komponenten.

```python
def set_license(self, stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | En ström som innehåller licensen. |

### Anmärkningar

Använd den här metoden för att läsa in en licens från en ström.

### Se också
* klass [`License`](/slides/python-net/sv/aspose.slides/license)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)