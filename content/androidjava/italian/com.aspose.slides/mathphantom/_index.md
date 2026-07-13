---
title: MathPhantom
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un oggetto matematico phantom ltmphantgt che influisce sul layout del suo elemento figlio senza necessariamente visualizzarlo.
type: docs
url: /it/com.aspose.slides/mathphantom/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Rappresenta un oggetto matematico phantom (<m:phant>) che influisce sul layout del suo elemento figlio senza necessariamente visualizzarlo. Un phantom può nascondere la sua espressione di base mantenendo la sua larghezza, altezza o profondità per allineare le formule o riservare spazio. La visibilità e il comportamento della geometria sono controllati da proprietà come Show, ZeroWid, ZeroAsc, ZeroDesc e Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Nascondi il contenuto
>  phantom.setZeroWidth(false);     // Mantieni la larghezza
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Inizializza una nuova istanza della classe [MathPhantom](../../com.aspose.slides/mathphantom) utilizzando l'elemento matematico di base specificato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento di base |
| [getShow()](#getShow--) | Ottiene o imposta un valore che indica se l'elemento di base è visualizzato. |
| [setShow(boolean value)](#setShow-boolean-) | Ottiene o imposta un valore che indica se l'elemento di base è visualizzato. |
| [getZeroWidth()](#getZeroWidth--) | Ottiene o imposta un valore che indica se la larghezza dell'elemento di base deve essere trattata come zero. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Ottiene o imposta un valore che indica se la larghezza dell'elemento di base deve essere trattata come zero. |
| [getZeroAsc()](#getZeroAsc--) | Ottiene o imposta un valore che indica se l'ascesa (altezza sopra la linea di base) dell'elemento di base deve essere trattata come zero. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Ottiene o imposta un valore che indica se l'ascesa (altezza sopra la linea di base) dell'elemento di base deve essere trattata come zero. |
| [getZeroDesc()](#getZeroDesc--) | Ottiene o imposta un valore che indica se la discesa (profondità sotto la linea di base) dell'elemento di base deve essere trattata come zero. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Ottiene o imposta un valore che indica se la discesa (profondità sotto la linea di base) dell'elemento di base deve essere trattata come zero. |
| [getTransp()](#getTransp--) | Ottiene o imposta un valore che indica se il phantom è trasparente per le regole di spaziatura basate su classi. |
| [setTransp(boolean value)](#setTransp-boolean-) | Ottiene o imposta un valore che indica se il phantom è trasparente per le regole di spaziatura basate su classi. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Proprietà del carattere di controllo |
| [getChildren()](#getChildren--) | Ottieni gli elementi figli |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

Inizializza una nuova istanza della classe [MathPhantom](../../com.aspose.slides/mathphantom) utilizzando l'elemento matematico di base specificato.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'[IMathElement](../../com.aspose.slides/imathelement) di base la cui visibilità e layout saranno controllati dal phantom. Questo elemento definisce il contenuto che può essere nascosto o mostrato, pur influenzando l'allineamento geometrico della matematica circostante. |

--------------------

L'elemento phantom è usato per riservare o sopprimere lo spazio visivo della sua espressione di base senza necessariamente visualizzarlo. Corrisponde all'elemento OMML <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argomento di base

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

Ottiene o imposta un valore che indica se l'elemento di base è visualizzato.

--------------------

Quando false, l'elemento di base è nascosto ma può comunque occupare spazio a seconda di altre impostazioni del phantom. Corrisponde all'attributo OMML m:show.

**Restituisce:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

Ottiene o imposta un valore che indica se l'elemento di base è visualizzato.

--------------------

Quando false, l'elemento di base è nascosto ma può comunque occupare spazio a seconda di altre impostazioni del phantom. Corrisponde all'attributo OMML m:show.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

Ottiene o imposta un valore che indica se la larghezza dell'elemento di base deve essere trattata come zero.

--------------------

Quando true, il phantom non riserva spazio orizzontale per la sua base. Corrisponde all'attributo OMML m:zeroWid.

**Restituisce:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

Ottiene o imposta un valore che indica se la larghezza dell'elemento di base deve essere trattata come zero.

--------------------

Quando true, il phantom non riserva spazio orizzontale per la sua base. Corrisponde all'attributo OMML m:zeroWid.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

Ottiene o imposta un valore che indica se l'ascesa (altezza sopra la linea di base) dell'elemento di base deve essere trattata come zero.

--------------------

Quando true, il phantom non alza la linea di base della riga matematica circostante. Corrisponde all'attributo OMML m:zeroAsc.

**Restituisce:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

Ottiene o imposta un valore che indica se l'ascesa (altezza sopra la linea di base) dell'elemento di base deve essere trattata come zero.

--------------------

Quando true, il phantom non alza la linea di base della riga matematica circostante. Corrisponde all'attributo OMML m:zeroAsc.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

Ottiene o imposta un valore che indica se la discesa (profondità sotto la linea di base) dell'elemento di base deve essere trattata come zero.

--------------------

Quando true, il phantom non abbassa la linea di base della riga matematica circostante. Corrisponde all'attributo OMML m:zeroDesc.

**Restituisce:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

Ottiene o imposta un valore che indica se la discesa (profondità sotto la linea di base) dell'elemento di base deve essere trattata come zero.

--------------------

Quando true, il phantom non abbassa la linea di base della riga matematica circostante. Corrisponde all'attributo OMML m:zeroDesc.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

Ottiene o imposta un valore che indica se il phantom è trasparente per le regole di spaziatura basate su classi.

--------------------

Quando true, gli operatori e i simboli all'interno del phantom influenzano ancora la spaziatura matematica intorno al phantom (come se fosse visibile). Quando false, la spaziatura basata su classi è ignorata. Corrisponde all'attributo OMML m:transp.

**Restituisce:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

Ottiene o imposta un valore che indica se il phantom è trasparente per le regole di spaziatura basate su classi.

--------------------

Quando true, gli operatori e i simboli all'interno del phantom influenzano ancora la spaziatura matematica intorno al phantom (come se fosse visibile). Quando false, la spaziatura basata su classi è ignorata. Corrisponde all'attributo OMML m:transp.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Proprietà del carattere di controllo

**Restituisce:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Ottieni gli elementi figli

**Restituisce:**
com.aspose.slides.IMathElement[]