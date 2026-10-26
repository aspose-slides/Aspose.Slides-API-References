---
title: set_BeginningCharacter()
second_title: Referencia de API de Aspose.Slides para C++
description: "El carácter inicial del delimitador especifica el carácter de delimitador de comienzo, o de apertura. Los delimitadores matemáticos son caracteres envolventes como paréntesis, corchetes y llaves. El valor predeterminado: '('."
type: docs
weight: 27
url: /es/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) método


El carácter inicial del delimitador especifica el carácter de delimitador de inicio, o de apertura. Los delimitadores matemáticos son caracteres que encierran, como paréntesis, corchetes y llaves. El valor predeterminado: '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
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