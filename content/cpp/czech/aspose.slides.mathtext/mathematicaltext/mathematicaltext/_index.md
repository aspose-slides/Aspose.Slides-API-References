---
title: MathematicalText()
second_title: Aspose.Slides pro C++ referenční dokumentace API
description: "Výchozí konstruktor (vytvoří hodnotu String::Empty)"
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() konstruktor


Výchozí konstruktor (vytvoří prázdnou hodnotu String::Empty)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## Poznámky


Příklad: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) konstruktor


Vytvořte [MathText](../../) s jedním znakem

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathSymbol | char16_t | single symbol |
## Poznámky



Příklad: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) konstruktor


Vytvořte [MathematicalText](../) z textu

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | text value |
## Poznámky



Příklad: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) konstruktor


Vytvořte [MathematicalText](../) z textu a nastavení formátu

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | text value |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | text format settings |
## Poznámky



Příklad: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [MathematicalText](../)
* třída [String](../../../system/string/)
* třída [IPortionFormat](../../../aspose.slides/iportionformat/)
* jmenný prostor [Aspose::Slides::MathText](../../)
* knihovna [Aspose.Slides](../../../)