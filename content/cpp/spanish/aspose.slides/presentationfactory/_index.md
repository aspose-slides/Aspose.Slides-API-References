---
title: PresentationFactory
second_title: Referencia de la API de Aspose.Slides para C++
description: Permite crear presentaciones mediante la interfaz COM
type: docs
weight: 4850
url: /es/aspose.slides/presentationfactory/
---
## PresentationFactory clase


Permite crear presentaciones a través de la interfaz COM

```cpp
class PresentationFactory : public Aspose::Slides::IPresentationFactory
```

## Métodos

| Método | Descripción |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [CreatePresentation](./createpresentation/)() override | Crea una nueva presentación. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [CreatePresentation](./createpresentation/)([System::SharedPtr](../../system/sharedptr/)\<[ILoadOptions](../iloadoptions/)\>) override | Crea una nueva presentación con opciones de carga adicionales |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| static [System::SharedPtr](../../system/sharedptr/)\<[PresentationFactory](./)\> [get_Instance](./get_instance/)() | [Presentation](../presentation/) instancia estática de fábrica. Solo lectura [PresentationFactory](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita el hashing de objetos personalizados. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationInfo](../ipresentationinfo/)\> [GetPresentationInfo](./getpresentationinfo/)([System::String](../../system/string/)) override | Crea un nuevo objeto [PresentationInfo](../presentationinfo/) a partir de un archivo y enlaza la presentación a él. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationInfo](../ipresentationinfo/)\> [GetPresentationInfo](./getpresentationinfo/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Crea un nuevo objeto [PresentationInfo](../presentationinfo/) a partir de un flujo y enlaza la presentación a él. Obtiene información sobre la presentación en el flujo especificado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationText](../ipresentationtext/)\> [GetPresentationText](./getpresentationtext/)([System::String](../../system/string/), [TextExtractionArrangingMode](../textextractionarrangingmode/)) override | Recupera el texto sin formato de las diapositivas |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationText](../ipresentationtext/)\> [GetPresentationText](./getpresentationtext/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [TextExtractionArrangingMode](../textextractionarrangingmode/)) override | Recupera el texto sin formato de las diapositivas |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationText](../ipresentationtext/)\> [GetPresentationText](./getpresentationtext/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [TextExtractionArrangingMode](../textextractionarrangingmode/), [System::SharedPtr](../../system/sharedptr/)\<[ILoadOptions](../iloadoptions/)\>) override | Recupera el texto sin formato de las diapositivas |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llámese directamente o use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita la clonación de tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Lee una presentación existente desde una matriz |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[ILoadOptions](../iloadoptions/)\>) override | Lee una presentación existente desde una matriz con opciones de carga adicionales |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Lee una presentación existente desde un flujo |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ILoadOptions](../iloadoptions/)\>) override | Lee una presentación existente desde un flujo con opciones de carga adicionales |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::String](../../system/string/)) override | Lee una presentación existente desde un archivo |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ILoadOptions](../iloadoptions/)\>) override | Lee una presentación existente desde un flujo con opciones de carga adicionales |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrece y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Habilita la conversión de objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llámese directamente o use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrece el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
## Observaciones


El siguiente ejemplo muestra cómo comprobar un formato [Presentation](../presentation/). 
```cpp
System::SharedPtr<IPresentationInfo> info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
System::Console::WriteLine(System::ExplicitCast<System::Object>(info->get_LoadFormat())); // PPTX
System::SharedPtr<IPresentationInfo> info2 = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.ppt");
System::Console::WriteLine(System::ExplicitCast<System::Object>(info2->get_LoadFormat())); // PPT
System::SharedPtr<IPresentationInfo> info3 = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.odp");
System::Console::WriteLine(System::ExplicitCast<System::Object>(info3->get_LoadFormat())); // ODP
```
 El siguiente ejemplo muestra cómo obtener las propiedades de un [Presentation](../presentation/). 
```cpp
System::SharedPtr<IPresentationInfo> info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
System::SharedPtr<IDocumentProperties> props = info->ReadDocumentProperties();
System::Console::WriteLine(System::ExplicitCast<System::Object>(props->get_CreatedTime()));
System::Console::WriteLine(props->get_Subject());
System::Console::WriteLine(props->get_Title());
```
 El siguiente ejemplo muestra cómo actualizar las propiedades de un [Presentation](../presentation/). 
```cpp
System::SharedPtr<IPresentationInfo> info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
System::SharedPtr<IDocumentProperties> props = info->ReadDocumentProperties();
props->set_Title(u"My title");
info->UpdateDocumentProperties(props);
```

## Ver también

* Clase [IPresentationFactory](../ipresentationfactory/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)