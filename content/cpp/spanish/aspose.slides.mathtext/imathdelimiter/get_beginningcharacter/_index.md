---
title: get_BeginningCharacter()
second_title: Referencia de API de Aspose.Slides para C++
description: "El carácter de inicio del delimitador especifica el carácter delimitador inicial, o de apertura. Los delimitadores matemáticos son caracteres de cierre como los paréntesis, corchetes y llaves. El valor predeterminado: '('."
type: docs
weight: 14
url: /es/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() método


El carácter de inicio del delimitador especifica el carácter delimitador inicial, o de apertura. Los delimitadores matemáticos son caracteres de cierre como los paréntesis, corchetes y llaves. El valor predeterminado: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## Observaciones


Ejemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Ver también

* Clase [IMathDelimiter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)