---
title: set_EndingCharacter()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Delimiter Ending Character especifica el carácter delimitador de final, o de cierre. Los delimitadores matemáticos son caracteres de encierro como paréntesis, corchetes y llaves. El valor predeterminado: ')'."
type: docs
weight: 79
url: /es/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) método

Delimiter Ending Character especifica el carácter delimitador de final, o de cierre. Los delimitadores matemáticos son caracteres de encierro como paréntesis, corchetes y llaves. El valor predeterminado: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
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