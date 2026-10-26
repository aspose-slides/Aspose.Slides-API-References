---
title: IMathPhantom
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un oggetto matematico fantasma ltmphantgt che influisce sul layout del suo elemento figlio senza necessariamente visualizzarlo.
type: docs
url: /it/com.aspose.slides/imathphantom/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Rappresenta un oggetto matematico fantasma (<m:phant>) che influenza il layout del suo elemento figlio senza necessariamente visualizzarlo. Un fantasma può nascondere l'espressione di base preservando la sua larghezza, altezza o profondità per allineare le formule o riservare spazio. La visibilità e il comportamento geometrico sono controllati da proprietà come Show, ZeroWid, ZeroAsc, ZeroDesc e Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Nascondi il contenuto
>  phantom.setZeroWidth(false);     // Mantieni la larghezza
>  ```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento di base |
| [getShow()](#getShow--) | Ottiene o imposta un valore che indica se l'elemento di base è visualizzato. |
| [setShow(boolean value)](#setShow-boolean-) | Ottiene o imposta un valore che indica se l'elemento di base è visualizzato. |
| [getZeroWidth()](#getZeroWidth--) | Ottiene o imposta un valore che indica se la larghezza dell'elemento di base deve essere considerata zero. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Ottiene o imposta un valore che indica se la larghezza dell'elemento di base deve essere considerata zero. |
| [getZeroAsc()](#getZeroAsc--) | Ottiene o imposta un valore che indica se l'ascesa (altezza sopra la linea di base) dell'elemento di base deve essere considerata zero. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Ottiene o imposta un valore che indica se l'ascesa (altezza sopra la linea di base) dell'elemento di base deve essere considerata zero. |
| [getZeroDesc()](#getZeroDesc--) | Ottiene o imposta un valore che indica se la discesa (profondità sotto la linea di base) dell'elemento di base deve essere considerata zero. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Ottiene o imposta un valore che indica se la discesa (profondità sotto la linea di base) dell'elemento di base deve essere considerata zero. |
| [getTransp()](#getTransp--) | Ottiene o imposta un valore che indica se il fantasma è trasparente per le regole di spaziatura basate su classi. |
| [setTransp(boolean value)](#setTransp-boolean-) | Ottiene o imposta un valore che indica se il fantasma è trasparente per le regole di spaziatura basate su classi. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argomento di base

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```


**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

Ottiene o imposta un valore che indica se l'elemento di base è visualizzato.

--------------------

Quando è false, l'elemento di base è nascosto ma può comunque occupare spazio a seconda di altre impostazioni del fantasma. Corrisponde all'attributo OMML m:show.

**Restituisce:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

Ottiene o imposta un valore che indica se l'elemento di base è visualizzato.

--------------------

Quando è false, l'elemento di base è nascosto ma può comunque occupare spazio a seconda di altre impostazioni del fantasma. Corrisponde all'attributo OMML m:show.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

Ottiene o imposta un valore che indica se la larghezza dell'elemento di base deve essere considerata zero.

--------------------

Quando è true, il fantasma non riserva spazio orizzontale per la sua base. Corrisponde all'attributo OMML m:zeroWid.

**Restituisce:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

Ottiene o imposta un valore che indica se la larghezza dell'elemento di base deve essere considerata zero.

--------------------

Quando è true, il fantasma non riserva spazio orizzontale per la sua base. Corrisponde all'attributo OMML m:zeroWid.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

Ottiene o imposta un valore che indica se l'ascesa (altezza sopra la linea di base) dell'elemento di base deve essere considerata zero.

--------------------

Quando è true, il fantasma non alza la linea di base della riga matematica circostante. Corrisponde all'attributo OMML m:zeroAsc.

**Restituisce:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

Ottiene o imposta un valore che indica se l'ascesa (altezza sopra la linea di base) dell'elemento di base deve essere considerata zero.

--------------------

Quando è true, il fantasma non alza la linea di base della riga matematica circostante. Corrisponde all'attributo OMML m:zeroAsc.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

Ottiene o imposta un valore che indica se la discesa (profondità sotto la linea di base) dell'elemento di base deve essere considerata zero.

--------------------

Quando è true, il fantasma non abbassa la linea di base della riga matematica circostante. Corrisponde all'attributo OMML m:zeroDesc.

**Restituisce:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

Ottiene o imposta un valore che indica se la discesa (profondità sotto la linea di base) dell'elemento di base deve essere considerata zero.

--------------------

Quando è true, il fantasma non abbassa la linea di base della riga matematica circostante. Corrisponde all'attributo OMML m:zeroDesc.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

Ottiene o imposta un valore che indica se il fantasma è trasparente per le regole di spaziatura basate su classi.

--------------------

Quando è true, gli operatori e i simboli all'interno del fantasma influenzano ancora la spaziatura matematica attorno al fantasma (come se fosse visibile). Quando è false, la spaziatura basata su classi è ignorata. Corrisponde all'attributo OMML m:transp.

**Restituisce:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

Ottiene o imposta un valore che indica se il fantasma è trasparente per le regole di spaziatura basate su classi.

--------------------

Quando è true, gli operatori e i simboli all'interno del fantasma influenzano ancora la spaziatura matematica attorno al fantasma (come se fosse visibile). Quando è false, la spaziatura basata su classi è ignorata. Corrisponde all'attributo OMML m:transp.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |