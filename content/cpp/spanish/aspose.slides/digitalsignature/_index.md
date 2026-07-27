---
title: DigitalSignature
second_title: Aspose.Slides para la referencia de API de C++
description: Firma digital en archivo firmado.
type: docs
weight: 768
url: /es/aspose.slides/digitalsignature/
---
## DigitalSignature clase


Firma digital en un archivo firmado.

```cpp
class DigitalSignature : public Aspose::Slides::IDigitalSignature
```

## Métodos

| Método | Descripción |
| --- | --- |
|  [DigitalSignature](./digitalsignature/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/)\>) | Crea un nuevo objeto [DigitalSignature](./) con el certificado especificado. |
|  [DigitalSignature](./digitalsignature/)([System::String](../../system/string/), [System::String](../../system/string/)) | Crea un nuevo objeto [DigitalSignature](./) con la ruta al archivo de certificado y la contraseña especificados. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales a pesar de que, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales a pesar de que, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/)\> [get_Certificate](./get_certificate/)() override | Objeto de certificado que se utilizó para firmar el documento. Solo lectura [X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | El propósito de la firma. Lee [System::String](../../system/string/). |
| **bool** [get_IsValid](./get_isvalid/)() override | Si esta firma digital es válida y el documento no ha sido manipulado, este valor será verdadero. Solo lectura **bool**. |
| [System::DateTime](../../system/datetime/) [get_SignTime](./get_signtime/)() override | La hora en que se firmó el documento. Solo lectura [System::DateTime](../../system/datetime/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método [Object.GetHashCode()](../../system/object/gethashcode/) de C#. Permite el hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada [System.Object.GetType()](../../system/object/gettype/) de C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador 'is' de C#. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o utilice el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | El propósito de la firma. Escribe [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método [Object.ToString()](../../system/object/tostring/) de C#. Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o utilice el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
## Observaciones


El siguiente ejemplo muestra cómo agregar una firma digital desde un certificado PFX en PowerPoint [Presentation](../presentation/). 
```cpp
// Inicializar instancia de Presentation
auto pres = System::MakeObject<Presentation>();

// Crear objeto DigitalSignature con archivo PFX y contraseña PFX
System::SharedPtr<DigitalSignature> signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
// Comentario de nueva firma digital
signature->set_Comments(u"Aspose.Slides digital signing test.");
// Agregar firma digital a la presentación
pres->get_DigitalSignatures()->Add(signature);
// Guardar presentación
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```
 El siguiente código de ejemplo muestra cómo validar la firma digital de PowerPoint [Presentation](../presentation/). 
```cpp
// Inicializar instancia de Presentation
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");

if (pres->get_DigitalSignatures()->get_Count() > 0)
{
    bool allSignaturesAreValid = true;
    System::Console::WriteLine(u"Signatures used to sign the presentation: ");
    // Verificar si todas las firmas digitales son válidas
    for (auto&& signature : System::IterateOver(pres->get_DigitalSignatures()))
    {
        System::Console::WriteLine(signature->get_Certificate()->get_SubjectName()->get_Name() + u", " +
                                   signature->get_SignTime().ToString(u"yyyy-MM-dd HH:mm") + u" -- " +
                                   (signature->get_IsValid() ? System::String(u"VALID") : System::String(u"INVALID")));
        allSignaturesAreValid &= signature->get_IsValid();
    }

    if (allSignaturesAreValid)
    {
        System::Console::WriteLine(u"Presentation is genuine, all signatures are valid.");
    }
    else
    {
        System::Console::WriteLine(u"Presentation has been modified since signing.");
    }
}
```

## Ver también

* Clase [IDigitalSignature](../idigitalsignature/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)