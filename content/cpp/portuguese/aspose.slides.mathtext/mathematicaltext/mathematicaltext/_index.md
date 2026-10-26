---
title: MathematicalText()
second_title: Referência da API Aspose.Slides para C++
description: "Construtor padrão (criar String::Empty Valor)"
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() construtor


Construtor padrão (criar String::Empty Valor)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## Observações


Exemplo: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) construtor


Criar [MathText](../../) com símbolo único

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathSymbol | char16_t | símbolo único |
## Observações



Exemplo: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) construtor


Criar [MathematicalText](../) a partir de texto

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valor de texto |
## Observações



Exemplo: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) construtor


Criar [MathematicalText](../) a partir de texto e configurações de formato

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valor de texto |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | configurações de formato de texto |
## Observações



Exemplo: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MathematicalText](../)
* Class [String](../../../system/string/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)