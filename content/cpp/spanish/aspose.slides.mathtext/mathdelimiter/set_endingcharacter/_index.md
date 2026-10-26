---
title: set_EndingCharacter()
second_title: Referencia de API de Aspose.Slides para C++
description: "Delimiter Ending Character especifica el carácter delimitador de finalización, o de cierre. Los delimitadores matemáticos son caracteres de contorno como paréntesis, corchetes y llaves. El valor predeterminado: ')'."
type: docs
weight: 79
url: /es/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) método

Delimiter Ending Character especifica el carácter delimitador de finalización, o de cierre. Los delimitadores matemáticos son caracteres de contorno como paréntesis, corchetes y llaves. El valor predeterminado: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```

## Observaciones

Ejemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Ver también

* Clase [MathDelimiter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)