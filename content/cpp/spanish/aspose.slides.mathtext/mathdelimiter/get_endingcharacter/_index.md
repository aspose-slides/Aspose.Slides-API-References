---
title: get_EndingCharacter()
second_title: Referencia de API de Aspose.Slides para C++
description: "Delimiter Ending Character especifica el carácter delimitador final, o de cierre. Los delimitadores matemáticos son caracteres envolventes como paréntesis, corchetes y llaves. El valor predeterminado: ')'."
type: docs
weight: 66
url: /es/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() método


Delimiter Ending Character especifica el carácter delimitador final, o de cierre. Los delimitadores matemáticos son caracteres envolventes como paréntesis, corchetes y llaves. El valor predeterminado: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
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