---
title: "System::IO"
second_title: Referencia de la API de Aspose.Slides para C++
description: 
type: docs
weight: 573
url: /es/system.io/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) | Representa un contenedor tipo [System.IO.Stream](./stream/) para std::basic_iostream y sus objetos derivados. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) | Representa un contenedor tipo [System.IO.Stream](./stream/) para std::basic_istream y sus objetos derivados. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) | Representa un contenedor tipo [System.IO.Stream](./stream/) para std::basic_ostream y sus objetos derivados. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) | Representa un búfer que envuelve flujos tipo [System::IO::Stream](./stream/) y permite que se utilicen como un búfer interno de flujos tipo std::iostream. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) | Representa un contenedor tipo std::iostream que utilizó [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) como búfer interno. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) | Representa un contenedor tipo std::istream que utilizó [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) como búfer interno. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) | Representa un contenedor tipo std::ostream que utilizó [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) como búfer interno. |
| [BinaryReader](./binaryreader/) | Representa un lector que lee tipos de datos primitivos como datos binarios en una codificación particular. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [BinaryWriter](./binarywriter/) | Representa un escritor que escribe valores de tipos primitivos a un flujo de bytes. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [BufferedStream](./bufferedstream/) | Agrega una capa de búfer sobre otro flujo. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [Details_DirectoryNotFoundException](./details_directorynotfoundexception/) |  |
| [Details_DriveNotFoundException](./details_drivenotfoundexception/) |  |
| [Details_EndOfStreamException](./details_endofstreamexception/) |  |
| [Details_FileLoadException](./details_fileloadexception/) |  |
| [Details_FileNotFoundException](./details_filenotfoundexception/) | La excepción que se lanza cuando un intento de acceder a un archivo que no existe en el disco falla. No cree instancias de esta clase manualmente. Utilice la clase FileNotFoundException en su lugar. Nunca envuelva las instancias de la clase FileNotFoundException en [System::SmartPtr](../system/smartptr/). |
| [Details_InvalidDataException](./details_invaliddataexception/) |  |
| [Details_IOException](./details_ioexception/) |  |
| [Details_PathTooLongException](./details_pathtoolongexception/) |  |
| [Directory](./directory/) | Contiene métodos para manipular directorios. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |
| [DirectoryInfo](./directoryinfo/) | Representa una ruta del sistema de archivos, un directorio referenciado por esta ruta y proporciona métodos de instancia para manipular directorios. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [File](./file/) | Proporciona métodos para manipular archivos. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |
| [FileInfo](./fileinfo/) | Representa una ruta a un archivo y un archivo referenciado por esta ruta y proporciona métodos para manipularlo. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [FileStream](./filestream/) | Representa un flujo de archivo que admite operaciones de lectura y escritura síncronas y asíncronas. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [FileSystemInfo](./filesysteminfo/) | La clase base para [FileInfo](./fileinfo/) y [DirectoryInfo](./directoryinfo/). Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [FileSystemInfoStat](./filesysteminfostat/) | Representa información sobre un archivo o directorio. |
| [MemoryStream](./memorystream/) | Representa un flujo que lee y escribe en memoria. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [Path](./path/) | Proporciona métodos para manipular rutas. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio. |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/) | Representa una clase base para contenedores tipo [System.IO.Stream](./stream/). Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [Stream](./stream/) | Una clase base para una variedad de implementaciones de flujos. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [StreamReader](./streamreader/) | Representa un lector que lee caracteres de un flujo de bytes. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [StreamWriter](./streamwriter/) | Representa un escritor que escribe caracteres a un flujo de bytes. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [StringReader](./stringreader/) | Representa un lector que lee caracteres de una cadena. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [StringWriter](./stringwriter/) | Implementa un [TextWriter](./textwriter/) que escribe información en una cadena. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [TextReader](./textreader/) | Una clase base para clases que representan lectores que leen secuencias de caracteres de distintas fuentes. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [TextWriter](./textwriter/) | Una clase base para clases que representan escritores que escriben secuencias de caracteres en distintos destinos. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/) | Proporciona acceso a memoria no administrada. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o mediante operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |

## Funciones

| Función | Descripción |
| --- | --- |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_istream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Función contenedora para flujos tipo std::basic_istream. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_ostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Función contenedora para flujos tipo std::basic_ostream. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_iostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/), [STDIOStreamPositionPreference](./stdiostreampositionpreference/)) | Función contenedora para flujos tipo std::basic_iostream. |

## Enumeraciones

| Enumeración | Descripción |
| --- | --- |
| [FileAccess](./fileaccess/) | Especifica el tipo de acceso al abrir el archivo. |
| [FileAttributes](./fileattributes/) | Representa los atributos de un directorio o un archivo. |
| [FileMode](./filemode/) | Especifica cómo debe abrirse un archivo. |
| [FileOptions](./fileoptions/) | Representa opciones avanzadas para crear el objeto [FileStream](./filestream/). |
| [FileShare](./fileshare/) | Especifica qué tipo de acceso pueden tener otros objetos [FileStream](./filestream/) a un archivo que se está abriendo. |
| [SearchOption](./searchoption/) | Especifica que la búsqueda debe realizarse solo en el directorio actual, o en el directorio actual y todos sus subdirectorios. |
| [SeekOrigin](./seekorigin/) | Especifica la posición de referencia en el flujo respecto a la cual se especifica la posición a la que buscar. |
| [STDIOStreamWrappingMode](./stdiostreamwrappingmode/) | Especifica el modo de operaciones de E/S que los contenedores ejecutarán sobre flujos tipo std::iostreams. |
| [STDIOStreamPositionPreference](./stdiostreampositionpreference/) | Determina qué posición en el flujo es preferible como posición común de lectura y escritura cuando std::basic_iostream y sus descendientes tendrán diferentes posiciones de lectura y escritura en el momento de crear el contenedor. |
| [SystemIOStreamWrappingMode](./systemiostreamwrappingmode/) | Especifica el modo de operaciones de E/S que los contenedores ejecutarán sobre flujos tipo [System::IO::Stream](./stream/). |

## Definiciones de tipo

| Definición de tipo | Descripción |
| --- | --- |
| [IOException](./ioexception/) |  |
| [EndOfStreamException](./endofstreamexception/) |  |
| [InvalidDataException](./invaliddataexception/) |  |
| [DirectoryNotFoundException](./directorynotfoundexception/) |  |
| [FileLoadException](./fileloadexception/) |  |
| [PathTooLongException](./pathtoolongexception/) |  |
| [DriveNotFoundException](./drivenotfoundexception/) |  |
| [BinaryWriterPtr](./binarywriterptr/) | Un alias para un puntero compartido a esta clase. |
| [FileNotFoundException](./filenotfoundexception/) | La excepción que se lanza cuando un intento de acceder a un archivo que no existe en el disco falla. Nunca envuelva las instancias de la clase FileNotFoundException en [System::SmartPtr](../system/smartptr/). |
| [STDIStreamWrapper](./stdistreamwrapper/) | Especializaciones de [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) para tipos de caracteres char. |
| [STDWIStreamWrapper](./stdwistreamwrapper/) | Especializaciones de [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) para **wchar_t** tipos de caracteres. |
| [STDOStreamWrapper](./stdostreamwrapper/) | Especializaciones de [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) para tipos de caracteres char. |
| [STDWOStreamWrapper](./stdwostreamwrapper/) | Especializaciones de [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) para **wchar_t** tipos de caracteres. |
| [STDIOStreamWrapper](./stdiostreamwrapper/) | Especializaciones de [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) para tipos de caracteres char. |
| [STDWIOStreamWrapper](./stdwiostreamwrapper/) | Especializaciones de [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) para **wchar_t** tipos de caracteres. |
| [SystemIStreamWrapper](./systemistreamwrapper/) | Especializaciones de [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) para tipos de caracteres char. |
| [SystemWIStreamWrapper](./systemwistreamwrapper/) | Especializaciones de [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) para **wchar_t** tipos de caracteres. |
| [SystemOStreamWrapper](./systemostreamwrapper/) | Especializaciones de [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) para tipos de caracteres char. |
| [SystemWOStreamWrapper](./systemwostreamwrapper/) | Especializaciones de [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) para **wchar_t** tipos de caracteres. |
| [SystemIOStreamWrapper](./systemiostreamwrapper/) | Especializaciones de [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) para tipos de caracteres char. |
| [SystemWIOStreamWrapper](./systemwiostreamwrapper/) | Especializaciones de [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) para **wchar_t** tipos de caracteres. |