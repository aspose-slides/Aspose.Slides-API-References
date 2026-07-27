---
title: set_BeginningCharacter()
second_title: Referencia de API de Aspose.Slides para C++
description: "El carácter inicial del delimitador especifica el carácter de comienzo, o de apertura, del delimitador. Los delimitadores matemáticos son caracteres de contorno como paréntesis, corchetes y llaves. El valor predeterminado: '('."
type: docs
weight: 27
url: /es/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) método

Delimiter Beginning Character especifica el carácter de inicio, o de apertura, del delimitador. Los delimitadores matemáticos son caracteres de contorno como paréntesis, corchetes y llaves. El valor predeterminado: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
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