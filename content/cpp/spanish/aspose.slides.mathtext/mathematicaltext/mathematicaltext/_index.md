---
title: MathematicalText()
second_title: "Referencia de API de Aspose.Slides para C++"
description: "Constructor predeterminado (crea String::Empty valor)"
type: docs
weight: 40
url: /es/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() constructor

Constructor predeterminado (crea String::Empty valor)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## Observaciones

Ejemplo: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) constructor

Crear [MathText](../../) con un símbolo único

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathSymbol | char16_t | símbolo único |
## Observaciones

Ejemplo: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) constructor

Crear [MathematicalText](../) a partir de texto

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valor de texto |
## Observaciones

Ejemplo: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) constructor

Crear [MathematicalText](../) a partir de texto y configuraciones de formato

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valor de texto |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | configuraciones de formato de texto |
## Observaciones

Ejemplo: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [MathematicalText](../)
* Clase [String](../../../system/string/)
* Clase [IPortionFormat](../../../aspose.slides/iportionformat/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)