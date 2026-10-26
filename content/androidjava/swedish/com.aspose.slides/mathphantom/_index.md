---
title: MathPhantom
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett phantom matematiskt objekt ltmphantgt som påverkar layouten för dess underordnade element utan att nödvändigtvis visa det.
type: docs
url: /sv/com.aspose.slides/mathphantom/
---
**Arv:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Representerar ett fantom-matematiskt objekt (<m:phant>) som påverkar layouten för dess underordnade element utan att nödvändigtvis visa det. Ett fantom kan dölja sitt basuttryck samtidigt som det bevarar sin bredd, höjd eller djup för att justera formler eller reservera utrymme. Synlighet och geometribeteende styrs av egenskaper som Show, ZeroWid, ZeroAsc, ZeroDesc och Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Dölj innehållet
>  phantom.setZeroWidth(false);     // Behåll bredden
> ```
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Initialiserar en ny instans av [MathPhantom](../../com.aspose.slides/mathphantom) klass med den angivna basmatematiska elementet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Basargument |
| [getShow()](#getShow--) | Hämtar eller anger ett värde som anger om baselementet visas. |
| [setShow(boolean value)](#setShow-boolean-) | Hämtar eller anger ett värde som anger om baselementet visas. |
| [getZeroWidth()](#getZeroWidth--) | Hämtar eller anger ett värde som anger om bredden på baselementet ska behandlas som noll. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Hämtar eller anger ett värde som anger om bredden på baselementet ska behandlas som noll. |
| [getZeroAsc()](#getZeroAsc--) | Hämtar eller anger ett värde som anger om uppstigningen (höjden ovanför baslinjen) för baselementet ska behandlas som noll. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Hämtar eller anger ett värde som anger om uppstigningen (höjden ovanför baslinjen) för baselementet ska behandlas som noll. |
| [getZeroDesc()](#getZeroDesc--) | Hämtar eller anger ett värde som anger om nedstigningen (djupet under baslinjen) för baselementet ska behandlas som noll. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Hämtar eller anger ett värde som anger om nedstigningen (djupet under baslinjen) för baselementet ska behandlas som noll. |
| [getTransp()](#getTransp--) | Hämtar eller anger ett värde som anger om fantomet är transparent för klass-baserade avståndsregler. |
| [setTransp(boolean value)](#setTransp-boolean-) | Hämtar eller anger ett värde som anger om fantomet är transparent för klass-baserade avståndsregler. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
| [getChildren()](#getChildren--) | Get children elements |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```


Initialiserar en ny instans av [MathPhantom](../../com.aspose.slides/mathphantom) klass med det angivna basmattelementet.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Det bas[IMathElement](../../com.aspose.slides/imathelement) vars synlighet och layout kommer att styras av fantomet. Detta element definierar innehållet som kan döljas eller visas, samtidigt som det fortfarande påverkar den geometriska justeringen av den omgivande matematiken.

--------------------

Fantom-elementet används för att reservera eller undertrycka det visuella utrymmet för dess basuttryck utan att nödvändigtvis visa det. Det motsvarar OMML-elementet <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Basargument

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```


Hämtar eller anger ett värde som anger om baselementet visas.

--------------------

När falskt är baselementet gömt men kan fortfarande uppta utrymme beroende på andra fantominställningar. Motsvarar OMML-attributet m:show.

**Returnerar:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```


Hämtar eller anger ett värde som anger om baselementet visas.

--------------------

När falskt är baselementet gömt men kan fortfarande uppta utrymme beroende på andra fantominställningar. Motsvarar OMML-attributet m:show.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```


Hämtar eller anger ett värde som anger om bredden på baselementet ska behandlas som noll.

--------------------

När true reserverar inte fantomet horisontellt utrymme för sin bas. Motsvarar OMML-attributet m:zeroWid.

**Returnerar:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```


Hämtar eller anger ett värde som anger om bredden på baselementet ska behandlas som noll.

--------------------

När true reserverar inte fantomet horisontellt utrymme för sin bas. Motsvarar OMML-attributet m:zeroWid.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```


Hämtar eller anger ett värde som anger om uppstigningen (höjden ovanför baslinjen) för baselementet ska behandlas som noll.

--------------------

När true höjer inte fantomet baslinjen för den omgivande matematiken. Motsvarar OMML-attributet m:zeroAsc.

**Returnerar:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```


Hämtar eller anger ett värde som anger om uppstigningen (höjden ovanför baslinjen) för baselementet ska behandlas som noll.

--------------------

När true höjer inte fantomet baslinjen för den omgivande matematiken. Motsvarar OMML-attributet m:zeroAsc.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```


Hämtar eller anger ett värde som anger om nedstigningen (djupet under baslinjen) för baselementet ska behandlas som noll.

--------------------

När true sänker inte fantomet baslinjen för den omgivande matematiken. Motsvarar OMML-attributet m:zeroDesc.

**Returnerar:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```


Hämtar eller anger ett värde som anger om nedstigningen (djupet under baslinjen) för baselementet ska behandlas som noll.

--------------------

När true sänker inte fantomet baslinjen för den omgivande matematiken. Motsvarar OMML-attributet m:zeroDesc.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```


Hämtar eller anger ett värde som anger om fantomet är transparent för klass-baserade avståndsregler.

--------------------

När true påverkar operatorer och symboler inuti fantomet fortfarande matematiskt avstånd runt fantomet (som om de var synliga). När false ignoreras klass-baserade avstånd. Motsvarar OMML-attributet m:transp.

**Returnerar:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```


Hämtar eller anger ett värde som anger om fantomet är transparent för klass-baserade avståndsregler.

--------------------

När true påverkar operatorer och symboler inuti fantomet fortfarande matematiskt avstånd runt fantomet (som om de var synliga). När false ignoreras klass-baserade avstånd. Motsvarar OMML-attributet m:transp.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Control Character Properties

**Returnerar:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Get children elements

**Returnerar:**
com.aspose.slides.IMathElement[]