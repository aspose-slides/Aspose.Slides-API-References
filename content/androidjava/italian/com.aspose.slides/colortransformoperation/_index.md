---
title: ColorTransformOperation
second_title: Riferimento API Java di Aspose.Slides per Android
description: Definisce l'operazione di trasformazione del colore.
type: docs
url: /it/com.aspose.slides/colortransformoperation/
---
**Ereditarietà:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Definisce l'operazione di trasformazione del colore.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Tint](#Tint) | Applica una tinta al colore. |
| [Shade](#Shade) | Applica una sfumatura al colore. |
| [Complement](#Complement) | Modifica il colore in una complementare RGB. |
| [Inverse](#Inverse) | Modifica il colore in un colore invertito. |
| [Grayscale](#Grayscale) | Modifica il colore in un grigio con la stessa luminosità. |
| [SetAlpha](#SetAlpha) | Definisce un componente alfa del colore. |
| [AddAlpha](#AddAlpha) | Aggiunge il valore di un parametro a un componente alfa del colore. |
| [MultiplyAlpha](#MultiplyAlpha) | Moltiplica un componente alfa per il valore di un parametro. |
| [SetHue](#SetHue) | Modifica il componente tonalità del colore al valore di un parametro. |
| [AddHue](#AddHue) | Aggiunge il valore del parametro al componente tonalità del colore. |
| [MultiplyHue](#MultiplyHue) | Moltiplica un componente tonalità per il valore di un parametro. |
| [SetSaturation](#SetSaturation) | Modifica il componente saturazione del colore al valore di un parametro. |
| [AddSaturation](#AddSaturation) | Aggiunge il valore di un parametro al componente saturazione del colore. |
| [MultiplySaturation](#MultiplySaturation) | Moltiplica un componente saturazione per il valore di un parametro. |
| [SetLuminance](#SetLuminance) | Modifica il componente luminanza del colore al valore di un parametro. |
| [AddLuminance](#AddLuminance) | Aggiunge il valore di un parametro al componente luminanza del colore. |
| [MultiplyLuminance](#MultiplyLuminance) | Moltiplica un componente luminanza per il valore di un parametro. |
| [SetRed](#SetRed) | Modifica il componente rosso del colore al valore di un parametro. |
| [AddRed](#AddRed) | Aggiunge il valore di un parametro al componente rosso del colore. |
| [MultiplyRed](#MultiplyRed) | Moltiplica un componente rosso per un parametro. |
| [SetGreen](#SetGreen) | Modifica il componente verde del colore al valore di un parametro. |
| [AddGreen](#AddGreen) | Aggiunge un parametro al componente verde del colore. |
| [MultiplyGreen](#MultiplyGreen) | Moltiplica un componente verde per il valore di un parametro. |
| [SetBlue](#SetBlue) | Modifica il componente blu del colore al valore di un parametro. |
| [AddBlue](#AddBlue) | Aggiunge il valore di un parametro al componente blu del colore. |
| [MultiplyBlue](#MultiplyBlue) | Moltiplica un componente blu per il valore di un parametro. |
| [Gamma](#Gamma) | Correzione gamma. |
| [InverseGamma](#InverseGamma) | Correzione gamma inversa. |
### Tint {#Tint}
```
public static final int Tint
```


Applica una tinta al colore. Il parametro è compreso tra 0 (colore originale) e 1 (bianco).

### Shade {#Shade}
```
public static final int Shade
```


Applica una sfumatura al colore. Il parametro è compreso tra 0 (colore originale) e 1 (nero).

### Complement {#Complement}
```
public static final int Complement
```


Modifica il colore in una complementare RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```


Modifica il colore in un colore invertito. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


Modifica il colore in un grigio con la stessa luminosità. Parametro ignorato.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```


Definisce un componente alfa del colore. Il parametro è compreso tra 0 (trasparente) e 1 (opaco).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```


Aggiunge il valore di un parametro a un componente alfa del colore. Il parametro è compreso tra -1 e 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```


Moltiplica un componente alfa per il valore di un parametro.

### SetHue {#SetHue}
```
public static final int SetHue
```


Modifica il componente tonalità del colore al valore di un parametro. Il parametro è compreso tra 0 e 360.

### AddHue {#AddHue}
```
public static final int AddHue
```


Aggiunge il valore del parametro al componente tonalità del colore. Il parametro è compreso tra -360 e 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```


Moltiplica un componente tonalità per il valore di un parametro.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```


Modifica il componente saturazione del colore al valore di un parametro. Il parametro è compreso tra 0 e 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```


Aggiunge il valore di un parametro al componente saturazione del colore. Il parametro è compreso tra -1 e 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```


Moltiplica un componente saturazione per il valore di un parametro.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```


Modifica il componente luminanza del colore al valore di un parametro. Il parametro è compreso tra 0 e 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```


Aggiunge il valore di un parametro al componente luminanza del colore. Il parametro è compreso tra -1 e 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```


Moltiplica un componente luminanza per il valore di un parametro.

### SetRed {#SetRed}
```
public static final int SetRed
```


Modifica il componente rosso del colore al valore di un parametro. Il parametro è compreso tra 0 e 1.

### AddRed {#AddRed}
```
public static final int AddRed
```


Aggiunge il valore di un parametro al componente rosso del colore. Il parametro è compreso tra -1 e 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```


Moltiplica un componente rosso per un parametro.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```


Modifica il componente verde del colore al valore di un parametro. Il parametro è compreso tra 0 e 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```


Aggiunge un parametro al componente verde del colore. Il parametro è compreso tra -1 e 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```


Moltiplica un componente verde per il valore di un parametro.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```


Modifica il componente blu del colore al valore di un parametro. Il parametro è compreso tra 0 e 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```


Aggiunge il valore di un parametro al componente blu del colore. Il parametro è compreso tra -1 e 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```


Moltiplica un componente blu per il valore di un parametro.

### Gamma {#Gamma}
```
public static final int Gamma
```


Correzione gamma. Parametro ignorato.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```


Correzione gamma inversa. Parametro ignorato.