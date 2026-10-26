---
title: set_license method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
Licensierar komponenten.

```python
def set_license(self, license_name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| license_name | **str** | Kan vara ett fullständigt eller kort filnamn eller namn på en inbäddad resurs.<br/><br/> Använd en tom sträng för att växla till testläge. |

### Anmärkningar

Försöker hitta licensen på följande platser:

1. Explicit sökväg.
2. Mappen för komponentens assembly.
3. Mappen för klientens anropande assembly.
4. Mappen för startassemblyn.
5. En inbäddad resurs i klientens anropande assembly.

**Obs:** På .NET Compact Framework, försöker hitta licensen endast på dessa platser:

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

Använd den här metoden för att ladda en licens från en ström.

### Se även
* klass [`ILicense`](/slides/python-net/sv/aspose.slides/ilicense)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)