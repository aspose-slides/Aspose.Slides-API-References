---
title: get_EndingCharacter()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Delimiter Ending Character especifica el carácter delimitador final o de cierre. Los delimitadores matemáticos son caracteres de contención como paréntesis, corchetes y llaves. El valor predeterminado: ')'."
type: docs
weight: 66
url: /es/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() método

Delimiter Ending Character especifica el carácter delimitador final o de cierre. Los delimitadores matemáticos son caracteres de contención como paréntesis, corchetes y llaves. El valor predeterminado: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```

## Observaciones

Ejemplo:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Ver también

* Clase [IMathDelimiter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)