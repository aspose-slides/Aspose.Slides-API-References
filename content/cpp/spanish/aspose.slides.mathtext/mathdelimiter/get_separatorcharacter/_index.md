---
title: get_SeparatorCharacter()
second_title: Referencia de API de Aspose.Slides para C++
description: "Delimiter Separator Character especifica el carácter que separa los argumentos en el objeto delimitador. El valor predeterminado: '|'."
type: docs
weight: 40
url: /es/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() método

Delimiter Separator Character especifica el carácter que separa los argumentos en el objeto delimitador. El valor predeterminado: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
```

## Observaciones

Ejemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Ver también

* Clase [MathDelimiter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)