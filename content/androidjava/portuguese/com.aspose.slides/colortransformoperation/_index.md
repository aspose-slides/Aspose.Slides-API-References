---
title: ColorTransformOperation
second_title: Aspose.Slides para Android via Referência da API Java
description: Define a operação de transformação de cor.
type: docs
url: /pt/com.aspose.slides/colortransformoperation/
---
**Herança:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Define a operação de transformação de cor.
## Campos

| Campo | Descrição |
| --- | --- |
| [Tint](#Tint) | Tinge a cor. |
| [Shade](#Shade) | Escurece a cor. |
| [Complement](#Complement) | Altera a cor para uma complementar RGB. |
| [Inverse](#Inverse) | Altera a cor para uma cor invertida. |
| [Grayscale](#Grayscale) | Altera a cor para um tom de cinza com a mesma luminosidade. |
| [SetAlpha](#SetAlpha) | Define um componente alfa da cor. |
| [AddAlpha](#AddAlpha) | Adiciona o valor de um parâmetro a um componente alfa da cor. |
| [MultiplyAlpha](#MultiplyAlpha) | Multiplica um componente alfa por um valor de parâmetro. |
| [SetHue](#SetHue) | Altera o componente de matiz da cor para o valor de um parâmetro. |
| [AddHue](#AddHue) | Adiciona o valor de um parâmetro ao componente de matiz da cor. |
| [MultiplyHue](#MultiplyHue) | Multiplica o componente de matiz por um valor de parâmetro. |
| [SetSaturation](#SetSaturation) | Altera o componente de saturação da cor para o valor de um parâmetro. |
| [AddSaturation](#AddSaturation) | Adiciona o valor de um parâmetro ao componente de saturação da cor. |
| [MultiplySaturation](#MultiplySaturation) | Multiplica o componente de saturação por um valor de parâmetro. |
| [SetLuminance](#SetLuminance) | Altera o componente de luminância da cor para o valor de um parâmetro. |
| [AddLuminance](#AddLuminance) | Adiciona o valor de um parâmetro ao componente de luminância da cor. |
| [MultiplyLuminance](#MultiplyLuminance) | Multiplica o componente de luminância por um valor de parâmetro. |
| [SetRed](#SetRed) | Altera o componente vermelho da cor para o valor de um parâmetro. |
| [AddRed](#AddRed) | Adiciona o valor de um parâmetro ao componente vermelho da cor. |
| [MultiplyRed](#MultiplyRed) | Multiplica o componente vermelho por um parâmetro. |
| [SetGreen](#SetGreen) | Altera o componente verde da cor para o valor de um parâmetro. |
| [AddGreen](#AddGreen) | Adiciona um parâmetro ao componente verde da cor. |
| [MultiplyGreen](#MultiplyGreen) | Multiplica o componente verde por um valor de parâmetro. |
| [SetBlue](#SetBlue) | Altera o componente azul da cor para o valor de um parâmetro. |
| [AddBlue](#AddBlue) | Adiciona o valor de um parâmetro ao componente azul da cor. |
| [MultiplyBlue](#MultiplyBlue) | Multiplica o componente azul por um valor de parâmetro. |
| [Gamma](#Gamma) | Correção gama. |
| [InverseGamma](#InverseGamma) | Correção gama inversa. |
### Tint {#Tint}
```
public static final int Tint
```

Tinge a cor. O parâmetro está no intervalo entre 0 (cor original) e 1 (branco).

### Shade {#Shade}
```
public static final int Shade
```

Escurece a cor. O parâmetro está no intervalo entre 0 (cor original) e 1 (preto).

### Complement {#Complement}
```
public static final int Complement
```

Altera a cor para uma complementar RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

Altera a cor para uma cor invertida. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

Altera a cor para um tom de cinza com a mesma luminosidade. Parâmetro ignorado.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

Define um componente alfa da cor. O parâmetro está no intervalo entre 0 (transparente) e 1 (opaco).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Adiciona o valor de um parâmetro a um componente alfa da cor. O parâmetro está no intervalo entre -1 e 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Multiplica um componente alfa por um valor de parâmetro.

### SetHue {#SetHue}
```
public static final int SetHue
```

Altera o componente de matiz da cor para o valor de um parâmetro. O parâmetro está no intervalo entre 0 e 360.

### AddHue {#AddHue}
```
public static final int AddHue
```

Adiciona o valor de um parâmetro ao componente de matiz da cor. O parâmetro está no intervalo entre -360 e 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Multiplica o componente de matiz por um valor de parâmetro.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

Altera o componente de saturação da cor para o valor de um parâmetro. O parâmetro está no intervalo entre 0 e 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Adiciona o valor de um parâmetro ao componente de saturação da cor. O parâmetro está no intervalo entre -1 e 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Multiplica o componente de saturação por um valor de parâmetro.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

Altera o componente de luminância da cor para o valor de um parâmetro. O parâmetro está no intervalo entre 0 e 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Adiciona o valor de um parâmetro ao componente de luminância da cor. O parâmetro está no intervalo entre -1 e 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Multiplica o componente de luminância por um valor de parâmetro.

### SetRed {#SetRed}
```
public static final int SetRed
```

Altera o componente vermelho da cor para o valor de um parâmetro. O parâmetro está no intervalo entre 0 e 1.

### AddRed {#AddRed}
```
public static final int AddRed
```

Adiciona o valor de um parâmetro ao componente vermelho da cor. O parâmetro está no intervalo entre -1 e 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

Multiplica o componente vermelho por um parâmetro.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

Altera o componente verde da cor para o valor de um parâmetro. O parâmetro está no intervalo entre 0 e 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

Adiciona um parâmetro ao componente verde da cor. O parâmetro está no intervalo entre -1 e 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Multiplica o componente verde por um valor de parâmetro.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

Altera o componente azul da cor para o valor de um parâmetro. O parâmetro está no intervalo entre 0 e 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

Adiciona o valor de um parâmetro ao componente azul da cor. O parâmetro está no intervalo entre -1 e 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Multiplica o componente azul por um valor de parâmetro.

### Gamma {#Gamma}
```
public static final int Gamma
```

Correção gama. Parâmetro ignorado.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Correção gama inversa. Parâmetro ignorado.