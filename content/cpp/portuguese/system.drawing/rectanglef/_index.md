---
title: RectangleF
second_title: Referência da API Aspose.Slides para C++
description: "Representa uma área retangular de uma imagem definida como coordenadas X e Y de ponto flutuante de precisão simples do canto superior esquerdo e sua largura e altura. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 248
url: /pt/system.drawing/rectanglef/
---
## RectangleF classe

Representa uma área retangular de uma imagem definida como coordenadas X e Y de ponto flutuante de precisão simples do canto superior esquerdo e sua largura e altura. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use [System::SmartPtr](../../system/smartptr/) classe para gerenciar objetos deste tipo.

```cpp
class RectangleF
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | Determina se o ponto especificado está localizado dentro do retângulo representado pelo objeto atual. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | Determina se o ponto especificado está localizado dentro do retângulo representado pelo objeto atual. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | Determina se o retângulo especificado está localizado dentro do retângulo representado pelo objeto atual. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | Determina se os retângulos representados pelo objeto atual e pelo objeto especificado são idênticos. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | Constrói um novo objeto [RectangleF](./) que representa um retângulo com as localizações das bordas especificadas. |
| **float** [get_Bottom](./get_bottom/)() const | Retorna a coordenada y da borda inferior do retângulo representado pelo objeto atual. |
| **float** [get_Height](./get_height/)() const | Retorna a altura do retângulo representado pelo objeto atual. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina se as coordenadas X e Y do canto superior esquerdo do retângulo representado pelo objeto atual, bem como sua largura e altura, têm valores iguais a 0. |
| **float** [get_Left](./get_left/)() const | Retorna a coordenada X da borda esquerda do retângulo representado pelo objeto atual. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | Retorna uma instância da classe [PointF](../pointf/) que especifica a localização do canto superior esquerdo do retângulo representado pelo objeto atual. |
| **float** [get_Right](./get_right/)() const | Retorna a coordenada X da borda direita do retângulo representado pelo objeto atual. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | Retorna uma instância da classe [SizeF](../sizef/) que especifica a largura e a altura do retângulo representado pelo objeto atual. |
| **float** [get_Top](./get_top/)() const | Retorna a coordenada Y da borda superior do retângulo representado pelo objeto atual. |
| **float** [get_Width](./get_width/)() const | Retorna a largura do retângulo representado pelo objeto atual. |
| **float** [get_X](./get_x/)() const | Retorna a coordenada X do canto superior esquerdo do retângulo representado pelo objeto atual. |
| **float** [get_Y](./get_y/)() const | Retorna a coordenada Y do canto superior esquerdo do retângulo representado pelo objeto atual. |
| int [GetHashCode](./gethashcode/)() const | Retorna um código hash do objeto atual. |
| void [Inflate](./inflate/)(**float**, **float**) | Aumenta a largura e a altura do retângulo representado pelo objeto atual, mantendo a localização do centro geométrico do retângulo. A largura e a altura são aumentadas em ambas as direções pelos valores especificados. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | Aumenta a largura e a altura do retângulo representado pelo objeto atual, mantendo a localização do centro geométrico do retângulo. A largura e a altura são aumentadas em ambas as direções pelos valores de largura e altura do objeto de tamanho especificado, respectivamente. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | Aumenta a largura e a altura do retângulo representado pelo objeto especificado, mantendo a localização do centro geométrico do retângulo. A largura e a altura são aumentadas em ambas as direções pelos valores especificados. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | Substitui o retângulo representado pelo objeto atual pelo retângulo que resulta da sua interseção com o retângulo representado pelo objeto especificado. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Retorna um retângulo que é resultado da interseção dos retângulos especificados. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | Determina se os retângulos representados pelos objetos atual e especificado se intersectam. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | Desloca a posição do retângulo representado pelo objeto atual pelos valores especificados. |
| void [Offset](./offset/)(**float**, **float**) | Desloca a posição do retângulo representado pelo objeto atual pelos valores especificados. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Sempre retorna true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Sempre retorna false. |
| [RectangleF](./rectanglef/)() | Constrói uma nova instância do objeto [RectangleF](./) que representa um retângulo com coordenadas X e Y e valores de largura e altura definidos como 0. |
| [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | Constrói uma nova instância do objeto [RectangleF](./) que representa um retângulo com as coordenadas especificadas do seu canto superior esquerdo e largura e altura. |
| [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | Constrói uma nova instância do objeto [RectangleF](./) que representa um retângulo com as coordenadas do canto superior esquerdo especificadas como uma instância da classe [PointF](../pointf/) e sua largura e altura como uma instância da classe [SizeF](../sizef/). |
| explicit [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | Constrói uma nova instância do objeto [RectangleF](./) que representa o retângulo equivalente ao especificado. |
| void [set_Height](./set_height/)(**float**) | Define a altura do retângulo representado pelo objeto atual. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | Define a localização do canto superior esquerdo do retângulo representado pelo objeto atual. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | Define a largura e a altura do retângulo representado pelo objeto atual. |
| void [set_Width](./set_width/)(**float**) | Define a largura do retângulo representado pelo objeto atual. |
| void [set_X](./set_x/)(**float**) | Define a coordenada X do canto superior esquerdo do retângulo representado pelo objeto atual. |
| void [set_Y](./set_y/)(**float**) | Define a coordenada Y do canto superior esquerdo do retângulo representado pelo objeto atual. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Retorna a representação em string do objeto atual. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Retorna um retângulo que é resultado da união dos retângulos especificados. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [Empty](./empty/) | Um retângulo vazio, ou seja, um retângulo cujos valores de localização e tamanho são zero. |

## Veja Também

* Espaço de nomes [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)