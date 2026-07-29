---
title: Equals()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om de två IBaseSlide-instanserna är lika. Returvärdet beräknas baserat på bildens struktur och statiska innehåll. Två bilder är lika om alla former, stilar, texter, animationer och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i Datumplatshållare.
type: docs
weight: 183
url: /sv/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) method


Bestämmer om de två [IBaseSlide](../)-instanserna är lika. Returvärdet beräknas baserat på bildens struktur och statiska innehåll. Två bilder är lika om alla former, stilar, texter, animationer och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i Date [Placeholder](../../placeholder/).

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | Den [IBaseSlide](../) som ska jämföras med den aktuella [IBaseSlide](../). |

### Returvärde

**true** om den angivna [IBaseSlide](../) är lika med den aktuella [IBaseSlide](../); annars **false**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IBaseSlide](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)