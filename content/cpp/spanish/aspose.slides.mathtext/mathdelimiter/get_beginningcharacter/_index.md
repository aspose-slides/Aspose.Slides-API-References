---
title: get_BeginningCharacter()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Delimiter Beginning Character especifica el carácter delimitador de inicio, o de apertura. Los delimitadores matemáticos son caracteres de cierre como los paréntesis, corchetes y llaves. El predeterminado: '('."
type: docs
weight: 14
url: /es/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() método

Delimiter Beginning Character especifica el carácter delimitador de inicio, o de apertura. Los delimitadores matemáticos son caracteres de cierre como los paréntesis, corchetes y llaves. El predeterminado: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## Observaciones

Ejemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Ver también

* Clase [MathDelimiter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)