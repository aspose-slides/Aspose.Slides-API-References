---
title: IMathPhantom
second_title: Aspose.Slides för Java API-referens
description: Representerar ett fantommatematiskt objekt ltmphantgt som påverkar layouten för dess underordnade element utan att nödvändigtvis visa det.
type: docs
url: /sv/com.aspose.slides/imathphantom/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Representerar ett fantommatematiskt objekt (<m:phant>) som påverkar layouten för dess underordnade element utan att nödvändigtvis visa det. Ett fantom kan dölja sitt basuttryck samtidigt som det bevarar sin bredd, höjd eller djup för att justera formler eller reservera utrymme. Synlighet och geometribeteende styrs av egenskaper såsom Show, ZeroWid, ZeroAsc, ZeroDesc och Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Dölj innehållet
>  phantom.setZeroWidth(false);     // Behåll bredden
>  ```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBase()](#getBase--) | Basargument |
| [getShow()](#getShow--) | Hämtar eller sätter ett värde som anger om baselementet visas. |
| [setShow(boolean value)](#setShow-boolean-) | Hämtar eller sätter ett värde som anger om baselementet visas. |
| [getZeroWidth()](#getZeroWidth--) | Hämtar eller sätter ett värde som anger om bredden på baselementet ska behandlas som noll. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Hämtar eller sätter ett värde som anger om bredden på baselementet ska behandlas som noll. |
| [getZeroAsc()](#getZeroAsc--) | Hämtar eller sätter ett värde som anger om ascent (höjd över baslinjen) för baselementet ska behandlas som noll. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Hämtar eller sätter ett värde som anger om ascent (höjd över baslinjen) för baselementet ska behandlas som noll. |
| [getZeroDesc()](#getZeroDesc--) | Hämtar eller sätter ett värde som anger om descent (djup under baslinjen) för baselementet ska behandlas som noll. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Hämtar eller sätter ett värde som anger om descent (djup under baslinjen) för baselementet ska behandlas som noll. |
| [getTransp()](#getTransp--) | Hämtar eller sätter ett värde som anger om fantomet är transparent för klassbaserade avståndsregler. |
| [setTransp(boolean value)](#setTransp-boolean-) | Hämtar eller sätter ett värde som anger om fantomet är transparent för klassbaserade avståndsregler. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Basargument

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```

**Returnerar:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

Hämtar eller sätter ett värde som anger om baselementet visas.

--------------------

När false är baselementet dolt men kan fortfarande upptaga utrymme beroende på andra fantominställningar. Motsvarar OMML-attributet m:show.

**Returnerar:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

Hämtar eller sätter ett värde som anger om baselementet visas.

--------------------

När false är baselementet dolt men kan fortfarande upptaga utrymme beroende på andra fantominställningar. Motsvarar OMML-attributet m:show.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

Hämtar eller sätter ett värde som anger om bredden på baselementet ska behandlas som noll.

--------------------

När true reserverar fantomet inte horisontellt utrymme för sin bas. Motsvarar OMML-attributet m:zeroWid.

**Returnerar:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

Hämtar eller sätter ett värde som anger om bredden på baselementet ska behandlas som noll.

--------------------

När true reserverar fantomet inte horisontellt utrymme för sin bas. Motsvarar OMML-attributet m:zeroWid.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

Hämtar eller sätter ett värde som anger om ascent (höjd över baslinjen) för baselementet ska behandlas som noll.

--------------------

När true höjer inte fantomet baslinjen för den omgivande matematikraden. Motsvarar OMML-attributet m:zeroAsc.

**Returnerar:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

Hämtar eller sätter ett värde som anger om ascent (höjd över baslinjen) för baselementet ska behandlas som noll.

--------------------

När true höjer inte fantomet baslinjen för den omgivande matematikraden. Motsvarar OMML-attributet m:zeroAsc.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

Hämtar eller sätter ett värde som anger om descent (djup under baslinjen) för baselementet ska behandlas som noll.

--------------------

När true sänker inte fantomet baslinjen för den omgivande matematikraden. Motsvarar OMML-attributet m:zeroDesc.

**Returnerar:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

Hämtar eller sätter ett värde som anger om descent (djup under baslinjen) för baselementet ska behandlas som noll.

--------------------

När true sänker inte fantomet baslinjen för den omgivande matematikraden. Motsvarar OMML-attributet m:zeroDesc.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

Hämtar eller sätter ett värde som anger om fantomet är transparent för klassbaserade avståndsregler.

--------------------

När true påverkar operatorer och symboler inne i fantomet fortfarande det matematiska avståndet runt fantomet (som om det var synligt). När false ignoreras klassbaserade avstånd. Motsvarar OMML-attributet m:transp.

**Returnerar:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

Hämtar eller sätter ett värde som anger om fantomet är transparent för klassbaserade avståndsregler.

--------------------

När true påverkar operatorer och symboler inne i fantomet fortfarande det matematiska avståndet runt fantomet (som om det var synligt). När false ignoreras klassbaserade avstånd. Motsvarar OMML-attributet m:transp.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |