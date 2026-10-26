---
title: IsDefined()
second_title: Aspose.Slides för C++ API-referens
description: INTE IMPLEMENTERAD. Anger om ett eller flera attribut av den angivna typen eller av dess härledda typer är tillämpade på denna medlem.
type: docs
weight: 157
url: /sv/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo\&, bool) const method


INTE IMPLEMENTERAD. Anger om ett eller flera attribut av den angivna typen eller av dess härledda typer är tillämpade på detta medlem.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Typen av anpassat attribut att söka efter. Sökningen inkluderar härledda typer. |
| inherit | **bool** | true för att söka i detta medlems arvskedja för att hitta attributen; annars false. Denna parameter ignoreras för egenskaper och händelser. |

### Return Value

true om ett eller flera instanser av attributeType eller någon av dess härledda typer är tillämpade på detta medlem; annars false.

## Se även

* Klass [TypeInfo](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)