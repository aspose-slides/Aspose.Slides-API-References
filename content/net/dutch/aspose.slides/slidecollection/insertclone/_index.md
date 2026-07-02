---
title: InsertClone
second_title: Aspose.Sildes voor .NET API-referentie
description: Voegt een kopie van een opgegeven dia toe op de opgegeven positie in de collectie.
type: docs
weight: 120
url: /nl/aspose.slides/slidecollection/insertclone/
---
## InsertClone(int, ISlide) {#insertclone}

Voegt een kopie van een opgegeven dia toe op de opgegeven positie in de collectie.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Index van de nieuwe dia. |
| sourceSlide | ISlide | Dia om te klonen. |

### Retourwaarde

Ingevoegde dia.

### Opmerkingen

Bij het klonen van een dia tussen verschillende presentaties kan ook de master van de dia worden gekloond. Een interne register wordt gebruikt om automatisch gekloonde masters bij te houden om het maken van meerdere klonen van dezelfde masterdia te voorkomen. Handmatig klonen van masterdia's wordt noch voorkomen noch geregistreerd. Als u meer controle over het kloonproces nodig heeft, gebruik dan [`InsertClone`](../insertclone) of [`InsertClone`](../insertclone) voor het klonen van dia's en [`AddClone`](../../imasterslidecollection/addclone) voor het klonen van masters.

### Voorbeelden

Het volgende voorbeeld laat zien hoe je op een andere positie binnen Presentation kunt klonen.

```csharp
[C#]
// Instantieer de Presentation-klasse die een presentatiebestand vertegenwoordigt
using (Presentation pres = new Presentation("CloneWithInSamePresentation.pptx"))
{
    // Kloon de gewenste dia naar het einde van de collectie dia's in dezelfde presentatie
    ISlideCollection slds = pres.Slides;
    // Kloon de gewenste dia naar de opgegeven index in dezelfde presentatie
    slds.InsertClone(2, pres.Slides[1]);
    // Schrijf de gewijzigde presentatie naar schijf
    pres.Save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
}
```

Het volgende voorbeeld laat zien hoe je op een andere positie binnen Presentation kunt klonen.

```csharp
[C#]
// Instantieer de Presentation-klasse om het bronpresentatiebestand te laden
using (Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx"))
{
    // Instantieer de Presentation-klasse voor de bestemmings-PPTX (waar de dia moet worden gekloond)
    using (Presentation destPres = new Presentation())
    {
        ISlideCollection slds = destPres.Slides;
        slds.InsertClone(2, srcPres.Slides[0]);
        // Schrijf de bestemmingspresentatie naar schijf
        destPres.Save("Aspose2_out.pptx", SaveFormat.Pptx);
    }
}
```

### Zie ook

* interface [ISlide](../../islide)
* klasse [SlideCollection](../../slidecollection)
* naamruimte [Aspose.Slides](../../slidecollection)
* assemblage [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, ILayoutSlide) {#insertclone_1}

Voegt een kopie van een opgegeven dia toe op de opgegeven positie in de collectie.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Index van de nieuwe dia. |
| sourceSlide | ISlide | Dia om te klonen. |
| destLayout | ILayoutSlide | Lay-outdia voor de nieuwe dia. |

### Retourwaarde

Ingevoegde dia.

### Zie ook

* interface [ISlide](../../islide)
* interface [ILayoutSlide](../../ilayoutslide)
* klasse [SlideCollection](../../slidecollection)
* naamruimte [Aspose.Slides](../../slidecollection)
* assemblage [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, IMasterSlide, bool) {#insertclone_2}

Voegt een kopie van een opgegeven brondia toe op de opgegeven positie in de collectie. Een geschikte lay-out wordt automatisch geselecteerd uit de opgegeven master (geschikte lay-out is de lay-out met hetzelfde Type of dezelfde Naam als van de lay-out van de brondia). Als er geen geschikte lay-out is, wordt de lay-out van de brondia gekloond (als allowCloneMissingLayout waar is) of wordt er een PptxEditException gegooid (als allowCloneMissingLayout onwaar is).

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, 
    bool allowCloneMissingLayout)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Index van de nieuwe dia. |
| sourceSlide | ISlide | Dia om te klonen. |
| destMaster | IMasterSlide | Masterdia voor de nieuwe dia. |
| allowCloneMissingLayout | Boolean | Als er geen geschikte lay-out is in de opgegeven master, wordt de lay-out van de brondia gekloond (als allowCloneMissingLayout waar is) of wordt er een PptxEditException gegooid (als allowCloneMissingLayout onwaar is). |

### Retourwaarde

Ingevoegde dia.

### Excepties

| exceptie | conditie |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Wordt gegooid als er geen geschikte lay-out is in de opgegeven master en allowCloneMissingLayout onwaar is. |

### Zie ook

* interface [ISlide](../../islide)
* interface [IMasterSlide](../../imasterslide)
* klasse [SlideCollection](../../slidecollection)
* naamruimte [Aspose.Slides](../../slidecollection)
* assemblage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->