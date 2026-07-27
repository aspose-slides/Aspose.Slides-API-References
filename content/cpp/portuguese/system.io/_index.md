---
title: "System::IO"
second_title: Aspose.Slides para C++ Referência da API
description: 
type: docs
weight: 573
url: /pt/system.io/
---
## Classes

| Classe | Descrição |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) | Representa um wrapper semelhante a [System.IO.Stream](./stream/) para std::basic_iostream e seus objetos derivados. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) | Representa um wrapper semelhante a [System.IO.Stream](./stream/) para std::basic_istream e seus objetos derivados. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) | Representa um wrapper semelhante a [System.IO.Stream](./stream/) para std::basic_ostream e seus objetos derivados. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) | Representa um buffer que envolve fluxos semelhantes a [System::IO::Stream](./stream/) e permite que eles sejam usados como buffer interno de fluxos semelhantes a std::iostream. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) | Representa um wrapper semelhante a std::iostream que utiliza [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) como buffer interno. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) | Representa um wrapper semelhante a std::istream que utiliza [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) como buffer interno. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) | Representa um wrapper semelhante a std::ostream que utiliza [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) como buffer interno. |
| [BinaryReader](./binaryreader/) | Representa um leitor que lê tipos de dados primitivos como dados binários em codificação específica. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [BinaryWriter](./binarywriter/) | Representa um gravador que grava valores de tipos primitivos em um fluxo de bytes. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [BufferedStream](./bufferedstream/) | Adiciona uma camada de buffer sobre outro fluxo. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [Details_DirectoryNotFoundException](./details_directorynotfoundexception/) |  |
| [Details_DriveNotFoundException](./details_drivenotfoundexception/) |  |
| [Details_EndOfStreamException](./details_endofstreamexception/) |  |
| [Details_FileLoadException](./details_fileloadexception/) |  |
| [Details_FileNotFoundException](./details_filenotfoundexception/) | A exceção lançada quando uma tentativa de acessar um arquivo que não existe no disco falha. Nunca crie instâncias desta classe manualmente. Use a classe FileNotFoundException em vez disso. Nunca envolva as instâncias da classe FileNotFoundException em [System::SmartPtr](../system/smartptr/). |
| [Details_InvalidDataException](./details_invaliddataexception/) |  |
| [Details_IOException](./details_ioexception/) |  |
| [Details_PathTooLongException](./details_pathtoolongexception/) |  |
| [Directory](./directory/) | Contém métodos para manipular diretórios. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio. |
| [DirectoryInfo](./directoryinfo/) | Representa um caminho de sistema de arquivos, um diretório referenciado por esse caminho e fornece métodos de instância para manipular diretórios. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [File](./file/) | Fornece métodos para manipular arquivos. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio. |
| [FileInfo](./fileinfo/) | Representa um caminho para um arquivo e um arquivo referenciado por esse caminho e fornece métodos para manipulá-lo. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [FileStream](./filestream/) | Representa um fluxo de arquivo que suporta operações síncronas e assíncronas de leitura e gravação. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [FileSystemInfo](./filesysteminfo/) | A classe base para [FileInfo](./fileinfo/) e [DirectoryInfo](./directoryinfo/). Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [FileSystemInfoStat](./filesysteminfostat/) | Representa informações sobre um arquivo ou diretório. |
| [MemoryStream](./memorystream/) | Representa um fluxo que lê e grava na memória. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [Path](./path/) | Fornece métodos para manipular caminhos. Este é um tipo estático sem serviços de instância. Você nunca deve criar instâncias dele por qualquer meio. |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/) | Representa uma classe base para wrappers semelhantes a [System.IO.Stream](./stream/). Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [Stream](./stream/) | Classe base para uma variedade de implementações de fluxo. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [StreamReader](./streamreader/) | Representa um leitor que lê caracteres de um fluxo de bytes. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [StreamWriter](./streamwriter/) | Representa um gravador que grava caracteres em um fluxo de bytes. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [StringReader](./stringreader/) | Representa um leitor que lê caracteres de uma string. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [StringWriter](./stringwriter/) | Implementa um [TextWriter](./textwriter/) que grava informações em uma string. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [TextReader](./textreader/) | Classe base para classes que representam leitores que leem sequências de caracteres de diferentes fontes. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [TextWriter](./textwriter/) | Classe base para classes que representam gravadores que escrevem sequências de caracteres em diferentes destinos. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/) | Fornece acesso à memória não gerenciada. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. |

## Funções

| Função | Descrição |
| --- | --- |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_istream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Função wrapper para fluxos semelhantes a std::basic_istream. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_ostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Função wrapper para fluxos semelhantes a std::basic_ostream. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_iostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/), [STDIOStreamPositionPreference](./stdiostreampositionpreference/)) | Função wrapper para fluxos semelhantes a std::basic_iostream. |

## Enumeradores

| Enumerador | Descrição |
| --- | --- |
| [FileAccess](./fileaccess/) | Especifica o tipo de acesso ao abrir o arquivo. |
| [FileAttributes](./fileattributes/) | Representa atributos de um diretório ou de um arquivo. |
| [FileMode](./filemode/) | Especifica como um arquivo deve ser aberto. |
| [FileOptions](./fileoptions/) | Representa opções avançadas para criar o objeto [FileStream](./filestream/). |
| [FileShare](./fileshare/) | Especifica que tipo de acesso outros objetos [FileStream](./filestream/) podem ter a um arquivo que está sendo aberto. |
| [SearchOption](./searchoption/) | Especifica que a busca deve ser realizada apenas no diretório atual, ou no diretório atual e em todos os seus subdiretórios. |
| [SeekOrigin](./seekorigin/) | Especifica a posição de referência no fluxo em relação à qual a posição a buscar é especificada. |
| [STDIOStreamWrappingMode](./stdiostreamwrappingmode/) | Especifica o modo de operações de I/O que os wrappers executarão em fluxos semelhantes a std::iostream. |
| [STDIOStreamPositionPreference](./stdiostreampositionpreference/) | Determina qual posição no fluxo é preferível como posição comum de leitura e escrita quando std::basic_iostream e seus descendentes terão posições de leitura e escrita diferentes no momento da criação do wrapper. |
| [SystemIOStreamWrappingMode](./systemiostreamwrappingmode/) | Especifica o modo de operações de I/O que os wrappers executarão em fluxos semelhantes a [System::IO::Stream](./stream/). |

## Tipos Definidos

| Typedef | Descrição |
| --- | --- |
| [IOException](./ioexception/) |  |
| [EndOfStreamException](./endofstreamexception/) |  |
| [InvalidDataException](./invaliddataexception/) |  |
| [DirectoryNotFoundException](./directorynotfoundexception/) |  |
| [FileLoadException](./fileloadexception/) |  |
| [PathTooLongException](./pathtoolongexception/) |  |
| [DriveNotFoundException](./drivenotfoundexception/) |  |
| [BinaryWriterPtr](./binarywriterptr/) | Um alias para um ponteiro compartilhado a esta classe. |
| [FileNotFoundException](./filenotfoundexception/) | A exceção lançada quando uma tentativa de acessar um arquivo que não existe no disco falha. Nunca envolva as instâncias da classe FileNotFoundException em [System::SmartPtr](../system/smartptr/). |
| [STDIStreamWrapper](./stdistreamwrapper/) | Especializações de [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) para tipos de caractere char. |
| [STDWIStreamWrapper](./stdwistreamwrapper/) | Especializações de [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) para tipos de caractere **wchar_t**. |
| [STDOStreamWrapper](./stdostreamwrapper/) | Especializações de [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) para tipos de caractere char. |
| [STDWOStreamWrapper](./stdwostreamwrapper/) | Especializações de [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) para tipos de caractere **wchar_t**. |
| [STDIOStreamWrapper](./stdiostreamwrapper/) | Especializações de [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) para tipos de caractere char. |
| [STDWIOStreamWrapper](./stdwiostreamwrapper/) | Especializações de [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) para tipos de caractere **wchar_t**. |
| [SystemIStreamWrapper](./systemistreamwrapper/) | Especializações de [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) para tipos de caractere char. |
| [SystemWIStreamWrapper](./systemwistreamwrapper/) | Especializações de [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) para tipos de caractere **wchar_t**. |
| [SystemOStreamWrapper](./systemostreamwrapper/) | Especializações de [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) para tipos de caractere char. |
| [SystemWOStreamWrapper](./systemwostreamwrapper/) | Especializações de [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) para tipos de caractere **wchar_t**. |
| [SystemIOStreamWrapper](./systemiostreamwrapper/) | Especializações de [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) para tipos de caractere char. |
| [SystemWIOStreamWrapper](./systemwiostreamwrapper/) | Especializações de [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) para tipos de caractere **wchar_t**. |