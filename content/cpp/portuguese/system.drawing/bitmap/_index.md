---
title: Bitmap
second_title: Referência da API Aspose.Slides para C++
description: "Representa uma imagem bitmap GDI+. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 1
url: /pt/system.drawing/bitmap/
---
## classe Bitmap

Representa uma imagem bitmap GDI+. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class Bitmap : public System::Drawing::Image
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | Ativa o modo de processamento de pixels. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | Constrói um novo objeto [Bitmap](./) a partir da imagem existente especificada. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | Constrói um novo objeto [Bitmap](./) a partir do fluxo especificado. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | Constrói um novo objeto [Bitmap](./) a partir do arquivo especificado. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | Constrói um novo objeto [Bitmap](./) a partir do arquivo especificado. |
| [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Constrói um novo objeto [Bitmap](./) que representa uma imagem bitmap com a largura, altura, formato de pixel e dados de pixel especificados. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | Constrói um novo objeto [Bitmap](./) a partir da imagem existente especificada, dimensionada ao tamanho especificado. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | Constrói um novo objeto [Bitmap](./) a partir da imagem existente especificada com largura e altura dimensionadas aos valores especificados. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | Cria uma cópia do objeto atual. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Cria um objeto [Bitmap](./) que representa uma cópia de uma região da imagem bitmap representada pelo objeto atual. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Cria um objeto [Bitmap](./) que representa uma cópia de uma região da imagem bitmap representada pelo objeto atual. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | Calcula o valor hash SHA1. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | Cria uma cópia da imagem bitmap especificada com o formato de pixel alterado para Format32bppArgb. |
| void [Dispose](../image/dispose/)() override | Libera todos os recursos adquiridos pelo objeto atual. |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | Desativa o modo de processamento de pixels. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | Cria um objeto [Image](../image/) a partir do arquivo especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | Constrói um objeto [Bitmap](./) a partir do bitmap GDI especificado. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Cria um objeto [Image](../image/) a partir do fluxo especificado. |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | Retorna uma combinação bit a bit dos valores da enumeração ImageFlags que representa os atributos da imagem. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | Retorna um array de GUIDs que representam as dimensões dos quadros dentro da imagem representada pelo objeto atual. |
| int [get_Height](./get_height/)() const override | Retorna a altura da imagem em pixels. |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | Retorna a resolução horizontal da imagem representada pelo objeto atual em pixels por polegada. |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | Retorna a paleta de cores usada pela imagem representada pelo objeto atual. |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | Retorna o formato de pixel da imagem representada pelo objeto atual. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | Obtém os IDs dos itens de propriedade armazenados nesta imagem. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | Obtém todos os itens de propriedade (metadados) armazenados nesta imagem. |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | Retorna o formato de arquivo da imagem representada pelo objeto atual. |
| [Size](../size/) [get_Size](../image/get_size/)() const | Retorna um objeto [Size](../size/) que representa a largura e a altura da imagem em pixels. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | Obtém um objeto que fornece dados adicionais sobre a imagem. |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | Retorna a resolução vertical da imagem representada pelo objeto atual em pixels por polegada. |
| int [get_Width](./get_width/)() const override | Retorna a largura da imagem em pixels. |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | Retorna os limites da imagem nas unidades de medida especificadas. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | Retorna o número de quadros da dimensão de quadro especificada. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hashing de objetos personalizados. |
| IntPtr [GetHbitmap](./gethbitmap/)() | Cria um objeto bitmap GDI a partir do bitmap representado pelo objeto atual. |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | Retorna a cor do pixel especificado. |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Retorna o número de bits usados para representar a profundidade de cor no formato de pixel especificado. |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | Retorna um ponteiro bruto para o objeto subjacente SkBitmap. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | Obtém uma miniatura para este objeto [System::Drawing::Image](../image/). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico do operador C# 'is'. |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Determina se o formato de pixel especificado contém informação alfa. |
| **bool** [IsMultiImage](./ismultiimage/)() const override | Retorna se o formato original é uma multi-imagem. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Bloqueia um [Bitmap](./) na memória do sistema. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Bloqueia um [Bitmap](./) na memória do sistema. |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | Altera a cor de todos os pixels da cor especificada para transparente. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita clonagem de tipos personalizados. |
| [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas internas de dados. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, apenas inicializa um novo objeto e habilita a construção de cópias nas subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, apenas inicializa um novo objeto e habilita a construção de cópias nas subclasses. |
| void [PremultipleColors](./premultiplecolors/)() | Pré-multiplica as cores dos pixels da imagem representada pelo objeto atual. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | Rotaciona a imagem em múltiplos de 90 graus e a inverte. |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | Salva a imagem representada pelo objeto atual no arquivo especificado em formato PNG. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Salva a imagem representada pelo objeto atual no arquivo especificado no formato especificado. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Salva a imagem representada pelo objeto atual no fluxo especificado no formato especificado. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Salva a imagem representada pelo objeto atual no arquivo especificado usando o codificador e os parâmetros de codificador especificados. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Salva a imagem representada pelo objeto atual no fluxo especificado usando o codificador e os parâmetros de codificador especificados. |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Adiciona um quadro ao arquivo ou fluxo especificado em uma chamada anterior ao método [Save()](../image/save/). |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Adiciona um quadro ao arquivo ou fluxo especificado em uma chamada anterior ao método [Save()](../image/save/). |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | Seleciona o quadro especificado. |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | Define a paleta de cores usada pela imagem representada pelo objeto atual. |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Define um objeto que fornece dados adicionais sobre a imagem. |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | Define a cor do pixel especificado na imagem bitmap representada pelo objeto atual. |
| void [SetResolution](./setresolution/)(**float**, **float**) | Define a resolução da imagem. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico do método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Desbloqueia o bitmap especificado da memória do sistema. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas internas de dados. |

## Veja Também

* Classe [Image](../image/)
* Namespace [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)