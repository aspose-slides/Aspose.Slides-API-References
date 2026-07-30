---
title: MathematicalText()
second_title: Riferimento API di Aspose.Slides per C++
description: "Costruttore predefinito (crea valore String::Empty)"
type: docs
weight: 40
url: /it/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() costruttore


Costruttore predefinito (crea valore String::Empty)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## Note


Esempio: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) costruttore


Crea [MathText](../../) con un singolo simbolo

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathSymbol | char16_t | simbolo singolo |
## Note



Esempio: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) costruttore


Crea [MathematicalText](../) dal testo

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valore di testo |
## Note



Esempio: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) costruttore


Crea [MathematicalText](../) dal testo e dalle impostazioni di formattazione

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valore di testo |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | impostazioni di formattazione del testo |
## Note



Esempio: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MathematicalText](../)
* Class [String](../../../system/string/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)