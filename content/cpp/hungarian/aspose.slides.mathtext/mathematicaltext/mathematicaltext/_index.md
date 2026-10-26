---
title: MathematicalText()
second_title: Aspose.Slides C++ API-referencia
description: "Alapértelmezett konstruktor (létrehozza a String::Empty értéket)"
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() konstruktor

Alapértelmezett konstruktor (hozzon létre String::Empty értéket)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## Megjegyzés

Példa: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) konstruktor

Létrehozza a [MathText](../../) egyetlen szimbólummal

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathSymbol | char16_t | egyetlen szimbólum |
## Megjegyzés



Példa: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) konstruktor

Létrehozza a [MathematicalText](../) szövegből

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | szövegérték |
## Megjegyzés



Példa: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) konstruktor

Létrehozza a [MathematicalText](../) szövegből és formátumbeállításokkal

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | szövegérték |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | szövegformátum beállítások |
## Megjegyzés



Példa: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MathematicalText](../)
* Class [String](../../../system/string/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)