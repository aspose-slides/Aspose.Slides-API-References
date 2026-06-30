---
title: MathBlock
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Inicjalizuje nową instancję klasy MathBlock.
type: docs
weight: 10
url: /pl/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock() {#constructor}

Inicjalizuje nową instancję klasy MathBlock.

```csharp
public MathBlock()
```

### Przykłady

Przykład:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Zobacz także

* klasa [MathBlock](../../mathblock)
* przestrzeń nazw [Aspose.Slides.MathText](../../mathblock)
* zestaw [Aspose.Slides](../../../)

---

## MathBlock(IMathElement) {#constructor_1}

Tworzy nowy blok matematyczny i umieszcza w nim określony element

```csharp
public MathBlock(IMathElement mathElement)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathElement | IMathElement | Element matematyczny do umieszczenia w bloku |

### Przykłady

Przykład:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
```

### Zobacz także

* interfejs [IMathElement](../../imathelement)
* klasa [MathBlock](../../mathblock)
* przestrzeń nazw [Aspose.Slides.MathText](../../mathblock)
* zestaw [Aspose.Slides](../../../)

---

## MathBlock(IEnumerable&lt;IMathElement&gt;) {#constructor_2}

Tworzy nowy blok matematyczny i umieszcza w nim określone elementy

```csharp
public MathBlock(IEnumerable<IMathElement> mathElements)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathElements | IEnumerable`1 | Elementy matematyczne do umieszczenia w bloku |

### Przykłady

Przykład:

```csharp
[C#]
var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
MathBlock mathBlock = new MathBlock(elems);
```

### Zobacz także

* interfejs [IMathElement](../../imathelement)
* klasa [MathBlock](../../mathblock)
* przestrzeń nazw [Aspose.Slides.MathText](../../mathblock)
* zestaw [Aspose.Slides](../../../)

<!-- NIE EDYTOWAĆ: wygenerowano przez xmldocmd dla Aspose.Slides.dll -->