---
title: set_SeparatorCharacter()
second_title: Referencia de API de Aspose.Slides para C++
description: "El carácter separador del delimitador especifica el carácter que separa los argumentos en el objeto delimitador. Valor predeterminado: '|'."
type: docs
weight: 53
url: /es/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) método


Delimiter Separator Character especifica el carácter que separa los argumentos en el objeto delimitador. El valor predeterminado: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
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