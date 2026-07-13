---
title: IMathPhantom
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett phantom-matematiskt objekt ltmphantgt som påverkar layouten för dess underordnade element utan att nödvändigtvis visa det.
type: docs
url: /sv/com.aspose.slides/imathphantom/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Representerar ett phantom-matematiskt objekt (<m:phant>) som påverkar layouten för dess underordnade element utan att nödvändigtvis visa det. En phantom kan dölja sitt basuttryck samtidigt som den bevarar sin bredd, höjd eller djup för att justera formler eller reservera utrymme. Synlighet och geometribeteende styrs av egenskaper såsom Show, ZeroWid, ZeroAsc, ZeroDesc och Transp.

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
| [getShow()](#getShow--) | Hämtar eller anger ett värde som visar om baselementet visas. |
| [setShow(boolean value)](#setShow-boolean-) | Hämtar eller anger ett värde som visar om baselementet visas. |
| [getZeroWidth()](#getZeroWidth--) | Hämtar eller anger ett värde som visar om bredden på baselementet ska behandlas som noll. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Hämtar eller anger ett värde som visar om bredden på baselementet ska behandlas som noll. |
| [getZeroAsc()](#getZeroAsc--) | Hämtar eller anger ett värde som visar om uppstigningen (höjden över baslinjen) på baselementet ska behandlas som noll. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Hämtar eller anger ett värde som visar om uppstigningen (höjden över baslinjen) på baselementet ska behandlas som noll. |
| [getZeroDesc()](#getZeroDesc--) | Hämtar eller anger ett värde som visar om nedstigningen (djupet under baslinjen) på baselementet ska behandlas som noll. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Hämtar eller anger ett värde som visar om nedstigningen (djupet under baslinjen) på baselementet ska behandlas som noll. |
| [getTransp()](#getTransp--) | Hämtar eller anger ett värde som visar om phantom är transparent för klassbaserade avståndsregler. |
| [setTransp(boolean value)](#setTransp-boolean-) | Hämtar eller anger ett värde som visar om phantom är transparent för klassbaserade avståndsregler. |
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

Hämtar eller anger ett värde som visar om baselementet visas.

--------------------

När falskt är baselementet dolt men kan fortfarande upptaga utrymme beroende på andra phantom-inställningar. Motsvarar OMML-attributet m:show.

**Returnerar:**
boolean

### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

Hämtar eller anger ett värde som visar om baselementet visas.

--------------------

När falskt är baselementet dolt men kan fortfarande upptaga utrymme beroende på andra phantom-inställningar. Motsvarar OMML-attributet m:show.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

Hämtar eller anger ett värde som visar om bredden på baselementet ska behandlas som noll.

--------------------

När sant reserverar phantom inte horisontellt utrymme för sin bas. Motsvarar OMML-attributet m:zeroWid.

**Returnerar:**
boolean

### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

Hämtar eller anger ett värde som visar om bredden på baselementet ska behandlas som noll.

--------------------

När sant reserverar phantom inte horisontellt utrymme för sin bas. Motsvarar OMML-attributet m:zeroWid.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

Hämtar eller anger ett värde som visar om uppstigningen (höjden över baslinjen) på baselementet ska behandlas som noll.

--------------------

När sant höjer phantom inte baslinjen för den omgivande matematisk raden. Motsvarar OMML-attributet m:zeroAsc.

**Returnerar:**
boolean

### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

Hämtar eller anger ett värde som visar om uppstigningen (höjden över baslinjen) på baselementet ska behandlas som noll.

--------------------

När sant höjer phantom inte baslinjen för den omgivande matematisk raden. Motsvarar OMML-attributet m:zeroAsc.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

Hämtar eller anger ett värde som visar om nedstigningen (djupet under baslinjen) på baselementet ska behandlas som noll.

--------------------

När sant sänker phantom inte baslinjen för den omgivande matematisk raden. Motsvarar OMML-attributet m:zeroDesc.

**Returnerar:**
boolean

### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

Hämtar eller anger ett värde som visar om nedstigningen (djupet under baslinjen) på baselementet ska behandlas som noll.

--------------------

När sant sänker phantom inte baslinjen för den omgivande matematisk raden. Motsvarar OMML-attributet m:zeroDesc.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

Hämtar eller anger ett värde som visar om phantom är transparent för klassbaserade avståndsregler.

--------------------

När sant påverkar operatorer och symboler inom phantom fortfarande matematisk avstånd runt phantom (som om den var synlig). När falskt ignoreras klassbaserad avståndsregler. Motsvarar OMML-attributet m:transp.

**Returnerar:**
boolean

### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

Hämtar eller anger ett värde som visar om phantom är transparent för klassbaserade avståndsregler.

--------------------

När sant påverkar operatorer och symboler inom phantom fortfarande matematisk avstånd runt phantom (som om den var synlig). När falskt ignoreras klassbaserad avståndsregler. Motsvarar OMML-attributet m:transp.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |