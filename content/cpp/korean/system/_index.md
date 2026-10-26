---
title: System
second_title: Aspose.Slides for C++ API 참조
description: 
type: docs
weight: 274
url: /ko/system/
---
## 클래스

| Class | Description |
| --- | --- |
| [Activator](./activator/) | 객체 유형을 생성하는 메서드를 포함합니다. |
| [Array](./array/) | 배열 데이터 구조를 나타내는 클래스입니다. [System::MakeArray()](./makearray/) 및 [System::MakeObject()](./makeobject/) 함수를 사용하여만 이 클래스의 객체를 할당해야 합니다. 런타임 오류 및/또는 어설션 오류를 초래하므로 스택에 이 유형의 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하도록 사용하십시오. |
| [ArrayBase](./arraybase/) | [System.Array](./array/) 클래스(모든 배열의 추상 기본 클래스)의 더미입니다. 요청에 따라 기능을 추가할 수 있습니다. |
| [ArraySegment](./arraysegment/) | 1차원 배열의 구간을 나타냅니다. 이 유형은 스택에 할당하고 값이나 참조로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용하여 이 유형의 객체를 관리해서는 안 됩니다. |
| [Attribute](./attribute/) | 사용자 지정 특성의 기본 클래스입니다. [System::MakeObject()](./makeobject/) 함수를 사용하여만 이 클래스의 객체를 할당해야 합니다. 런타임 오류 및/또는 어설션 오류를 초래하므로 스택에 이 유형의 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하도록 사용하십시오. |
| [BitConverter](./bitconverter/) | 바이트 시퀀스를 값 형식으로, 그리고 그 반대로 변환하는 메서드를 포함합니다. 이는 인스턴스 서비스를 제공하지 않는 정적 타입입니다. 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다. |
| [Boolean](./boolean/) | [System.Boolean](./boolean/) .[Net](../system.net/) 타입의 정적 멤버를 보관하는 클래스입니다. |
| [BoxedEnum](./boxedenum/) | 박싱된 열거형 값을 나타냅니다. [System::MakeObject()](./makeobject/) 함수를 사용하여만 이 클래스의 객체를 할당해야 합니다. 런타임 오류 및/또는 어설션 오류를 초래하므로 스택에 이 유형의 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하도록 사용하십시오. |
| [BoxedValue](./boxedvalue/) | 박싱된 값을 나타냅니다. [System::MakeObject()](./makeobject/) 함수를 사용하여만 이 클래스의 객체를 할당해야 합니다. 런타임 오류 및/또는 어설션 오류를 초래하므로 스택에 이 유형의 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하도록 사용하십시오. |
| [BoxedValue< ValueTuple< Args... > >](./boxedvalue_tmpl_valuetuple_tmpl_args_dots__end_tmpl__end_tmpl/) | 값 튜플의 박싱된 버전입니다. |
| [BoxedValueBase](./boxedvaluebase/) | 박싱된 값을 나타내는 파생 클래스의 인터페이스를 정의하고 일부 기본 메서드를 구현하는 기본 클래스입니다. [System::MakeObject()](./makeobject/) 함수를 사용하여만 이 클래스의 객체를 할당해야 합니다. 런타임 오류 및/또는 어설션 오류를 초래하므로 스택에 이 유형의 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하도록 사용하십시오. |
| [Buffer](./buffer/) | 원시 바이트 배열을 조작하는 메서드를 포함합니다. 이는 인스턴스 서비스를 제공하지 않는 정적 타입입니다. 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다. |
| [Byte](./byte/) | 부호 없는 8비트 정수와 작업하는 메서드를 포함합니다. |
| [Char](./char/) | UTF-16 코드 유닛으로 표현된 문자를 조작하는 메서드를 제공합니다. 이는 인스턴스 서비스를 제공하지 않는 정적 타입입니다. 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다. |
| [Comparison](./comparison/) | 동일한 유형의 두 객체를 비교하는 메서드에 대한 포인터를 나타냅니다. 이 유형은 스택에 할당하고 값이나 참조로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용하여 이 유형의 객체를 관리해서는 안 됩니다. |
| [Console](./console/) | 표준 출력 스트림에 데이터를 출력하는 메서드를 제공합니다. 이는 인스턴스 서비스를 제공하지 않는 정적 타입입니다. 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다. |
| [ConsoleOutput](./consoleoutput/) | 표준 출력 스트림을 나타냅니다. [System::MakeObject()](./makeobject/) 함수를 사용하여만 이 클래스의 객체를 할당해야 합니다. 런타임 오류 및/또는 어설션 오류를 초래하므로 스택에 이 유형의 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하도록 사용하십시오. |
| [DateTime](./datetime/) | 시간 연속체 상의 특정 날짜와 시간 값을 나타냅니다. 이 유형은 스택에 할당하고 값이나 참조로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용하여 이 유형의 객체를 관리해서는 안 됩니다. |
| [DateTimeOffset](./datetimeoffset/) | 협정 세계시(UTC)를 기준으로 하는 날짜와 시간 정보를 포함합니다. [System::MakeObject()](./makeobject/) 함수를 사용하여만 이 클래스의 객체를 할당해야 합니다. 런타임 오류 및/또는 어설션 오류를 초래하므로 스택에 이 유형의 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하도록 사용하십시오. |
| [DBNull](./dbnull/) | 존재하지 않는 값을 나타냅니다. [System::MakeObject()](./makeobject/) 함수를 사용하여만 이 클래스의 객체를 할당해야 합니다. 런타임 오류 및/또는 어설션 오류를 초래하므로 스택에 이 유형의 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하도록 사용하십시오. |
| [Decimal](./decimal/) | 십진수를 나타냅니다. 이 유형은 스택에 할당하고 값이나 참조로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용하여 이 유형의 객체를 관리해서는 안 됩니다. |
| [DefaultBoxedValue](./defaultboxedvalue/) | [BoxedValue](./boxedvalue/) 클래스 구현입니다. 공통 코드를 중복하지 않고 BoxingValue 특수화를 선언할 수 있도록 합니다. [System::MakeObject()](./makeobject/) 함수를 사용하여만 이 클래스의 객체를 할당해야 합니다. 런타임 오류 및/또는 어설션 오류를 초래하므로 스택에 이 유형의 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하도록 사용하십시오. |
| [Delegate< ReturnType(ArgumentTypes...)>](./delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | 함수, 메서드 또는 함수 객체에 대한 포인터를 나타냅니다. 이 유형은 스택에 할당하고 값이나 참조로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용하여 이 유형의 객체를 관리해서는 안 됩니다. |
| [Details_AggregateException](./details_aggregateexception/) | 여러 내부 예외를 포함하는 예외를 나타냅니다. |
| [Details_ApplicationException](./details_applicationexception/) | 애플리케이션(시스템이 아닌) 예외를 나타내는 클래스의 기본 클래스입니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 ApplicationException 클래스를 사용하십시오. ApplicationException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_ArgumentException](./details_argumentexception/) | ArgumentException은 호출된 메서드에 전달된 인수가 유효하지 않을 때 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 ArgumentException 클래스를 사용하십시오. ArgumentException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_ArgumentNullException](./details_argumentnullexception/) |  |
| [Details_ArgumentOutOfRangeException](./details_argumentoutofrangeexception/) | ArgumentOutOfRangeException은 호출된 메서드에 전달된 인수가 기대값 범위를 벗어났을 때 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 ArgumentOutOfRangeException 클래스를 사용하십시오. ArgumentOutOfRangeException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_ArithmeticException](./details_arithmeticexception/) | ArithmeticException은 산술 연산이나 형변환 수행 중 오류가 발생할 때 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 ArithmeticException 클래스를 사용하십시오. ArithmeticException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_BadImageFormatException](./details_badimageformatexception/) | 동적 연결 라이브러리(DLL) 또는 실행 파일의 이미지가 잘못되었을 때 발생하는 예외입니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 BadImageFormatException 클래스를 사용하십시오. BadImageFormatException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_DataMisalignedException](./details_datamisalignedexception/) |  |
| [Details_DivideByZeroException](./details_dividebyzeroexception/) | DivideByZeroException은 산술 연산에서 0으로 나누기를 시도할 때 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 DivideByZeroException 클래스를 사용하십시오. DivideByZeroException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_Exception](./details_exception/) | 예외를 나타냅니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 Exception 클래스를 사용하십시오. Exception 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_ExceptionWithErrorCode](./details_exceptionwitherrorcode/) | 오류 코드를 포함하는 예외에 대한 템플릿 클래스입니다. |
| [Details_ExceptionWithFilename](./details_exceptionwithfilename/) | 파일 이름을 포함하는 예외에 대한 템플릿 클래스입니다. |
| [Details_ExecutionEngineException](./details_executionengineexception/) | ExecutionEngineException은 호환성을 위해서만 존재합니다. |
| [Details_FormatException](./details_formatexception/) | FormatException은 메서드 인수의 형식이 유효하지 않을 때 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 FormatException 클래스를 사용하십시오. FormatException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_IndexOutOfRangeException](./details_indexoutofrangeexception/) | IndexOutOfRangeException은 컬렉션 요소에 대한 접근 시 인덱스가 범위를 벗어났을 때 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 IndexOutOfRangeException 클래스를 사용하십시오. IndexOutOfRangeException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_InvalidCastException](./details_invalidcastexception/) | InvalidCastException은 잘못된 명시적 변환을 시도할 때 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 InvalidCastException 클래스를 사용하십시오. InvalidCastException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_InvalidOperationException](./details_invalidoperationexception/) | 메서드가 호출된 객체의 상태가 해당 호출과 일치하지 않을 때 발생하는 예외입니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 InvalidOperationException 클래스를 사용하십시오. InvalidOperationException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_InvalidProgramException](./details_invalidprogramexception/) | InvalidProgramException은 호환성을 위해서만 존재합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 InvalidProgramException 클래스를 사용하십시오. InvalidProgramException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_InvalidTimeZoneException](./details_invalidtimezoneexception/) | InvalidTimeZoneException은 시간대 정보가 잘못되었을 때 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 InvalidTimeZoneException 클래스를 사용하십시오. InvalidTimeZoneException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_MemberAccessException](./details_memberaccessexception/) | MemberAccessException은 존재하지 않는 클래스 멤버에 접근을 시도하거나 접근이 허용되지 않을 때 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 MemberAccessException 클래스를 사용하십시오. MemberAccessException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_MethodAccessException](./details_methodaccessexception/) | MemberAccessException은 존재하지 않는 메서드에 접근을 시도하거나 접근이 허용되지 않을 때 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 MethodAccessException 클래스를 사용하십시오. MethodAccessException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_NotImplementedException](./details_notimplementedexception/) | NotImplementedException은 구현되지 않은 메서드(스텁)가 호출될 때 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 NotImplementedException 클래스를 사용하십시오. NotImplementedException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_NotSupportedException](./details_notsupportedexception/) | NotSupportedException은 호출된 메서드가 지원되지 않거나 스트림에서 수행된 연산이 지원되지 않을 때 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 NotSupportedException 클래스를 사용하십시오. NotSupportedException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_NullReferenceException](./details_nullreferenceexception/) | NullReferenceException은 null 참조를 역참조하려 할 때 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 NullReferenceException 클래스를 사용하십시오. NullReferenceException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_ObjectDisposedException](./details_objectdisposedexception/) | ObjectDisposedException은 폐기된 객체에서 메서드가 호출될 때 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 ObjectDisposedException 클래스를 사용하십시오. ObjectDisposedException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_OperationCanceledException](./details_operationcanceledexception/) | OperationCanceledException은 스레드가 실행 중이던 작업이 취소될 때 해당 스레드에서 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 OperationCanceledException 클래스를 사용하십시오. OperationCanceledException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_OutOfMemoryException](./details_outofmemoryexception/) |  |
| [Details_OverflowException](./details_overflowexception/) | OverflowException은 연산 결과가 오버플로우될 때 발생합니다. 이 클래스를 직접 인스턴스화해서는 안 됩니다. 대신 OverflowException 클래스를 사용하십시오. OverflowException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 감싸서는 안 됩니다. |
| [Details_PlatformNotSupportedException](./details_platformnotsupportedexception/) | PlatformNotSupportedException은 특정 플랫폼에서 기능이 실행되지 않을 때 발생합니다. 이 클래스를 직접 인스턴스화하지 마십시오. 대신 PlatformNotSupportedException 클래스를 사용하십시오. PlatformNotSupportedException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 절대로 래핑하지 마십시오. |
| [Details_RankException](./details_rankexception/) | RankException은 차원 수가 예상과 다른 배열 인수가 메서드에 전달될 때 발생합니다. 이 클래스를 직접 인스턴스화하지 마십시오. 대신 RankException 클래스를 사용하십시오. RankException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 절대로 래핑하지 마십시오. |
| [Details_StackOverflowException](./details_stackoverflowexception/) | StackOverflowException은 스레드의 실행 스택이 오버플로될 때 발생합니다. 이 클래스를 직접 인스턴스화하지 마십시오. 대신 StackOverflowException 클래스를 사용하십시오. StackOverflowException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 절대로 래핑하지 마십시오. |
| [Details_SystemException](./details_systemexception/) | 시스템(응용 프로그램이 아닌) 예외를 나타내는 클래스들의 기본 클래스입니다. 이 클래스를 직접 인스턴스화하지 마십시오. 대신 SystemException 클래스를 사용하십시오. SystemException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 절대로 래핑하지 마십시오. |
| [Details_TimeoutException](./details_timeoutexception/) | TimeoutException은 프로세스나 작업에 할당된 시간이 초과되었음을 나타냅니다. 이 클래스를 직접 인스턴스화하지 마십시오. 대신 TimeoutException 클래스를 사용하십시오. TimeoutException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 절대로 래핑하지 마십시오. |
| [Details_TimeZoneNotFoundException](./details_timezonenotfoundexception/) | TimeZoneNotFoundException은 시간대 정보를 찾을 수 없을 때 발생합니다. 이 클래스를 직접 인스턴스화하지 마십시오. 대신 TimeZoneNotFoundException 클래스를 사용하십시오. TimeZoneNotFoundException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 절대로 래핑하지 마십시오. |
| [Details_TypeInitializationException](./details_typeinitializationexception/) |  |
| [Details_UnauthorizedAccessException](./details_unauthorizedaccessexception/) | UnauthorizedAccessException은 I/O 오류나 보안 오류로 인해 운영 체제가 접근을 거부할 때 발생합니다. 이 클래스를 직접 인스턴스화하지 마십시오. 대신 UnauthorizedAccessException 클래스를 사용하십시오. UnauthorizedAccessException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 절대로 래핑하지 마십시오. |
| [Details_UriFormatException](./details_uriformatexception/) | UriFormatException은 URI 형식이 올바르지 않을 때 발생합니다. 이 클래스를 직접 인스턴스화하지 마십시오. 대신 UriFormatException 클래스를 사용하십시오. UriFormatException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 절대로 래핑하지 마십시오. |
| [DynamicWeakPtr](./dynamicweakptr/) | 스마트 포인터 클래스는 저장된 객체의 템플릿 인수 포인터 모드를 추적하고 각 할당 후에 업데이트합니다. 이 유형은 다른 객체의 삭제를 관리하는 포인터이며, 스택에 할당하고 값이나 const 레퍼런스로 함수에 전달해야 합니다. |
| [EnumValues](./enumvalues/) | 열거형 타입 **E**의 열거 상수에 대한 메타 정보를 제공합니다. |
| [EnumValuesBase](./enumvaluesbase/) | 열거형 타입의 메타 정보를 나타내는 클래스의 기본 클래스입니다. |
| [EventArgs](./eventargs/) | 이벤트가 발생할 때 구독자에게 전달되는 컨텍스트를 나타내는 클래스들의 기본 클래스입니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 사용해 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 및 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 래핑하고 해당 포인터를 함수 인자로 전달하십시오. |
| [ExceptionWrapper](./exceptionwrapper/) | Exception 클래스를 상속받은 예외를 래핑하는 템플릿입니다. |
| [FlagsAttribute](./flagsattribute/) | 열거형을 비트 필드, 즉 집합으로 취급할 수 있음을 나타냅니다. |
| [Func](./func/) | 함수 대리자. 이 유형은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용해 이 유형의 객체를 관리하지 마십시오. |
| [GC](./gc/) | 실제로 아무 작업도 수행하지 않는 스텁과 같은 에뮬레이션된 가비지 컬렉션을 나타냅니다. 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떤 방법으로도 인스턴스를 생성하면 안 됩니다. |
| [Guid](./guid/) | 전역 고유 식별자(GUID)를 나타냅니다. 이 유형은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용해 이 유형의 객체를 관리하지 마십시오. |
| [IAsyncResult](./iasyncresult/) | 비동기 작업의 상태를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 사용해 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 및 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 래핑하고 해당 포인터를 함수 인자로 전달하십시오. |
| [ICloneable](./icloneable/) | 객체 복제를 가능하게 하는 메서드를 정의합니다(객체 복사). 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 사용해 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 및 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 래핑하고 해당 포인터를 함수 인자로 전달하십시오. |
| [IComparable](./icomparable/) | 두 객체를 비교하는 메서드를 정의합니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 사용해 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 및 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 래핑하고 해당 포인터를 함수 인자로 전달하십시오. |
| [IConvertible](./iconvertible/) | 구현된 참조 또는 값 타입의 값을 동등한 CLR 타입으로 변환하는 메서드를 정의합니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 사용해 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 및 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 래핑하고 해당 포인터를 함수 인자로 전달하십시오. |
| [ICustomFormatter](./icustomformatter/) | 지정된 객체가 나타내는 값의 문자열 표현을 사용자 정의 형식화하는 메서드를 정의합니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 사용해 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 및 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 래핑하고 해당 포인터를 함수 인자로 전달하십시오. |
| [IDisposable](./idisposable/) | 현재 객체가 보유한 리소스를 해제하는 메서드를 정의합니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 사용해 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 및 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 래핑하고 해당 포인터를 함수 인자로 전달하십시오. |
| [IEquatable](./iequatable/) | 두 객체의 동등성을 판단하는 메서드를 정의합니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 사용해 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 및 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 래핑하고 해당 포인터를 함수 인자로 전달하십시오. |
| [IFormatProvider](./iformatprovider/) | 형식 정보를 제공하는 메서드를 정의합니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 사용해 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 및 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 래핑하고 해당 포인터를 함수 인자로 전달하십시오. |
| [IFormattable](./iformattable/) | 지정된 형식 문자열과 형식 공급자를 사용해 현재 객체의 값을 형식화하는 메서드를 정의합니다. |
| [Index](./index/) | 컬렉션의 인덱스를 나타냅니다. 인덱스는 앞쪽이나 뒤쪽에서 계산될 수 있습니다. 이 유형은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용해 이 유형의 객체를 관리하지 마십시오. |
| [Int16](./int16/) | 16비트 정수를 다루는 메서드를 포함합니다. |
| [Int32](./int32/) | 32비트 정수를 다루는 메서드를 포함합니다. |
| [Int64](./int64/) | 64비트 정수를 다루는 메서드를 포함합니다. |
| [LockContext](./lockcontext/) | C# lock() 구문을 구현하는 가드 객체입니다. |
| [MarshalByRefObject](./marshalbyrefobject/) | 리모팅이 활성화된 애플리케이션에서 애플리케이션 도메인 경계를 넘는 객체에 대한 접근을 제공합니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 사용해 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 및 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 래핑하고 해당 포인터를 함수 인자로 전달하십시오. |
| [MulticastDelegate< ReturnType(ArgumentTypes...)>](./multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | 대리자들의 컬렉션을 나타냅니다. 이 유형은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용해 이 유형의 객체를 관리하지 마십시오. |
| [Nullable](./nullable/) | 전방 선언입니다. |
| [NullableUtils](./nullableutils/) | C# [System.Nullable](./nullable/)(형식 인수가 없는) 정적 클래스를 나타냅니다. C++에서는 클래스 템플릿 오버로드가 불가능해 원래 이름을 사용할 수 없습니다. null을 할당할 수 있는 값 타입을 지원합니다. 이 클래스는 상속될 수 없습니다. |
| [Object](./object/) | [System.Object](./object/) 클래스의 메서드를 C#에서 사용할 수 있게 하는 기본 클래스입니다. 번역된 환경에서 사용되는 모든 비트리비얼(non-trivial) 클래스는 이를 상속해야 합니다. |
| [ObjectExt](./objectext/) | C# [Object](./object/) 메서드를 비-Object C++ 타입(문자열, 숫자 등)에서 에뮬레이트하는 정적 메서드를 제공합니다. 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떤 방법으로도 인스턴스를 생성하면 안 됩니다. |
| [ObjectType](./objecttype/) | 객체 타입 getter를 구현하는 정적 메서드를 제공합니다. 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떤 방법으로도 인스턴스를 생성하면 안 됩니다. |
| [OperatingSystem](./operatingsystem/) | 특정 운영 체제를 나타내고 해당 정보를 제공합니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 사용해 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 및 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 래핑하고 해당 포인터를 함수 인자로 전달하십시오. |
| [Random](./random/) | 의사 난수 생성기를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 사용해 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 및 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 래핑하고 해당 포인터를 함수 인자로 전달하십시오. |
| [Range](./range/) | 시작 인덱스와 끝 인덱스를 갖는 범위를 나타냅니다. 이 유형은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용해 이 유형의 객체를 관리하지 마십시오. |
| [ReadOnlySpan](./readonlyspan/) | [Span](./span/) 클래스 내에서 사용하기 위한 포워드입니다. |
| [ScopedCulture](./scopedculture/) | 범위 내에서 사용되는 문화권을 나타냅니다. |
| [SmartPtr](./smartptr/) | 힙에 할당되는 타입을 감싸는 포인터 클래스입니다. [Object](./object/)을 상속하는 클래스의 메모리를 관리하는 데 사용합니다. 이 포인터 유형은 침입형 포인터 의미를 따릅니다. 참조 카운터는 [Object](./object/) 자체에 저장되거나 [Object](./object/) 인스턴스와 밀접하게 연결된 카운터 구조에 저장됩니다. 어떤 경우든 모든 [SmartPtr](./smartptr/) 인스턴스는 생성 방식과 관계없이 단일 소유 그룹을 형성하며, 이는 std::shared_ptr 클래스가 동작하는 방식과 다릅니다. 같은 객체에 대한 공유 참조를 보유하고 있는 다른 [SmartPtr](./smartptr/) 인스턴스가 존재한다면 원시 포인터를 [SmartPtr](./smartptr/)로 변환하는 것은 안전합니다. [SmartPtr](./smartptr/) 클래스 인스턴스는 공유 포인터와 약한 포인터 두 상태 중 하나가 될 수 있습니다. 객체를 살아 있게 유지하려면 공유 참조 수가 양수이어야 합니다. 약한 포인터와 공유 포인터 모두 객체에 접근(메서드 호출, 필드 읽기·쓰기 등)할 수 있지만, 약한 포인터는 공유 포인터 참조 카운팅에 참여하지 않습니다. [Object](./object/)는 마지막 'shared' [SmartPtr](./smartptr/) 포인터가 파괴될 때 삭제됩니다. 따라서 객체에 대한 다른 공유 [SmartPtr](./smartptr/) 포인터가 존재하지 않을 때, 예를 들어 객체 생성 또는 소멸 중에 이러한 상황이 발생하지 않도록 해야 합니다. 이 문제를 해결하려면 C++ 코드에서는 System::Object::ThisProtector 감시 객체를, C# 코드(번역 중)에서는 CppCTORSelfReference 또는 CppSelfReference 특성을 사용하십시오. 마찬가지로 C++ 코드에서는 [System::WeakPtr](./weakptr/) 포인터 클래스 또는 [System::SmartPtrMode::Weak](./smartptrmode/) 포인터 모드를, C# 코드(번역 중)에서는 CppWeakPtr 특성을 사용하여 순환 참조를 끊도록 하십시오. 'shared' 포인터를 사용하여 두 개 이상 객체가 서로를 참조하면 절대 삭제되지 않습니다. 런타임에 포인터 타입(약한 또는 공유)을 전환해야 할 경우 [System::SmartPtr<T>::set_Mode()](./smartptr/set_mode/) 메서드 또는 [System::DynamicWeakPtr](./dynamicweakptr/) 클래스를 사용하십시오. [SmartPtr](./smartptr/) 클래스에는 가상 메서드가 없습니다. 자체 메모리 관리 전략을 만들 때만 이를 상속해야 합니다. 이 타입은 다른 객체의 삭제를 관리하는 포인터이며, 스택에 할당하고 값이나 const 레퍼런스로 함수에 전달해야 합니다. |
| [SmartPtrInfo](./smartptrinfo/) | 최종 타입을 알지 못한 상태에서 [SmartPtr](./smartptr/)의 내용을 테스트하고 수정하는 서비스 클래스입니다. 가비지 컬렉션 및 순환 참조 탐지 등에 사용됩니다. '포인터의 포인터'라고 생각하면 됩니다. [SmartPtr](./smartptr/)의 기본 타입을 사용할 수 없으므로, 대신 이 'info' 클래스를 사용합니다. |
| [Span](./span/) | 임의 메모리의 연속된 영역을 나타내며 C++20의 std::span과 유사합니다. |
| [String](./string/) | 라이브러리 전역에서 사용되는 [String](./string/) 클래스입니다. 코드 번역 시 C# [System.String](./string/)의 대체품입니다. 최적화 이유로 [Object](./object/)의 하위 클래스로 간주되지 않습니다. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오. |
| [StringComparer](./stringcomparer/) | 다양한 비교 모드를 사용하여 문자열을 비교합니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 통해서만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 감싸고 해당 포인터를 인자로 함수에 전달하십시오. |
| [StringHashCompiletime](./stringhashcompiletime/) | c-string에서 해시 값을 생성하는 도움 클래스입니다. |
| [TimeSpan](./timespan/) | 시간 구간을 나타냅니다. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오. |
| [TimeZone](./timezone/) | 시간대를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 통해서만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 감싸고 해당 포인터를 인자로 함수에 전달하십시오. |
| [TimeZoneInfo](./timezoneinfo/) | 특정 시간대에 대한 정보를 설명하는 정보를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 통해서만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 감싸고 해당 포인터를 인자로 함수에 전달하십시오. |
| [Tuple](./tuple/) | 튜플 데이터 구조를 나타내는 클래스입니다. 최대 아이템 수는 8개입니다. |
| [TupleFactory](./tuplefactory/) | 튜플 객체를 생성하기 위한 정적 메서드를 제공합니다. |
| [TypeInfo](./typeinfo/) | 특정 타입을 나타내며 해당 타입에 대한 정보를 제공합니다. |
| [Uri](./uri/) | 통합 자원 식별자입니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 통해서만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 감싸고 해당 포인터를 인자로 함수에 전달하십시오. |
| [UriBuilder](./uribuilder/) | 범용 자원 식별자(URI)를 생성하고 수정하는 메서드를 제공합니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 통해서만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 감싸고 해당 포인터를 인자로 함수에 전달하십시오. |
| [UriParser](./uriparser/) | 새로운 URI 스키마를 파싱하는 데 사용됩니다. 이 클래스의 객체는 [System::MakeObject()](./makeobject/) 함수를 통해서만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하면 런타임 오류 또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](./smartptr/) 포인터로 감싸고 해당 포인터를 인자로 함수에 전달하십시오. |
| [UriShim](./urishim/) | 서비스 클래스. |
| [ValueTuple](./valuetuple/) | [ValueTuple](./valuetuple/) 데이터 구조를 나타내는 클래스입니다. |
| [ValueType](./valuetype/) | [Object](./object/) 상속을 가진 값 타입의 기본 클래스이며, 성능 상 이유로 잘려 있습니다. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오. |
| [Version](./version/) | 버전 번호를 나타냅니다. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오. |
| [Void](./void/) |  |
| [WeakPtr](./weakptr/) | [System::SmartPtr](./smartptr/)의 하위 클래스로, 생성 시 자체를 약한 모드로 설정합니다. [set_Mode()](./smartptr/set_mode/)에 여전히 접근 가능하므로 이 클래스가 인스턴스를 항상 약한 모드로 유지한다는 보장은 없습니다. 이 타입은 다른 객체의 삭제를 관리하는 포인터이며, 스택에 할당하고 값이나 const 레퍼런스로 함수에 전달해야 합니다. |
| [WeakReference< T >](./weakreference_tmpl_t__end_tmpl/) | 객체를 참조하지만 해당 객체가 삭제될 수 있도록 허용하는 약한 참조를 나타냅니다. |
| [WeakReference<>](./weakreference_tmpl_end_tmpl/) | 객체를 참조하지만 해당 객체가 삭제될 수 있도록 허용하는 약한 참조를 나타냅니다. |

## 구조체

| 구조체 | 설명 |
| --- | --- |
| [CastResult](./castresult/) | 캐스트 결과를 추론하기 위한 템플릿 매직입니다. |
| [CollectionAssertHelper](./collectionasserthelper/) | 컬렉션 관련 연산을 위한 헬퍼 API입니다. |
| [Convert](./convert/) | 한 타입의 값을 다른 타입의 값으로 변환하는 메서드를 포함하는 구조체입니다. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오. |
| [Double](./double/) | 배정밀도 부동소수점 숫자를 다루는 메서드를 포함합니다. |
| [Enum](./enum/) | enum 타입 값에 대한 여러 연산을 수행하는 메서드를 제공합니다. 이 타입은 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떤 방식으로도 인스턴스를 생성해서는 안 됩니다. |
| [EnumGetNameHelper](./enumgetnamehelper/) | enum 상수의 문자열 이름을 얻는 기능을 제공하는 헬퍼 클래스입니다. |
| [EnumParseHelper](./enumparsehelper/) | enum 상수의 문자열 표현을 해당 enum 값으로 변환하는 기능을 제공하는 헬퍼 클래스입니다. |
| [Environment](./environment/) | [Environment](./environment/) 서비스를 제공합니다. 이 타입은 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떤 방식으로도 인스턴스를 생성해서는 안 됩니다. |
| [HolderInitializer](./holderinitializer/) | 이 클래스는 객체 인스턴스( lvalue든 rvalue든 )에 대한 지속적인 레퍼런스를 얻는 데 사용됩니다. 이러한 레퍼런스를 얻기 위해서는 'HoldIfTemporary' 메서드를 사용합니다. 이 메서드에는 세 개의 오버로드가 있습니다. 두 개는 rvalue를 매개변수로 받아 그대로 레퍼런스를 반환하고, 세 번째는 lvalue를 매개변수로 받아 포인터 복사를 만든 뒤 그 복사본에 대한 레퍼런스를 반환합니다. 또한 클래스에는 전달된 값을 무조건 보유하는 'Hold' 메서드가 있어, 스택에 있는 로컬 변수나 그 자식 레퍼런스의 값을 복사하는 데 사용됩니다. |
| [HolderInitializer< T, false >](./holderinitializer_tmpl_t__false__end_tmpl/) | [HolderInitializer](./holderinitializer/)가 T가 값 타입인 경우에 대한 특수화입니다. 사용 컨텍스트에서 임시 객체에 대한 레퍼런스를 반환할 수 있도록 보장되며, 인스턴스는 호출자에 의해 복사됩니다. 따라서 이 특수화는 단순히 스텁으로 사용되며 아무 동작도 하지 않습니다. |
| [IsBoxable](./isboxable/) | 지정된 타입에 대한 박싱이 지원되는지 확인하는 템플릿 프레디케이트입니다. |
| [IsExceptionWrapper](./isexceptionwrapper/) | 지정된 타입이 Exception 클래스 또는 그 파생 클래스인지 판단하는 템플릿 프레디케이트입니다. |
| [IsNullable](./isnullable/) | [Nullable](./nullable/) 또는 그 하위 클래스에 있는 템플릿 인수 T인지 판단하는 템플릿 프레디케이트입니다. |
| [IsSmartPtr](./issmartptr/) | [SmartPtr](./smartptr/) 클래스의 특수화인지 확인하는 트레이트 클래스입니다. |
| [IsStringByteSequence](./isstringbytesequence/) | 타입이 문자열 문자 시퀀스인지 확인하는 템플릿 매직입니다. |
| [IsStringLiteral](./isstringliteral/) | 타입이 문자열 리터럴인지 확인하는 템플릿 매직입니다. |
| [IsStringPointer](./isstringpointer/) | 타입이 문자 문자열에 대한 포인터인지 확인하는 템플릿 매직입니다. |
| [IsWeakPtr](./isweakptr/) | 특정 클래스가 [System::WeakPtr](./weakptr/)의 특수화인지 확인하는 트레이트 클래스이며, 인스턴스가 실제로 약한 모드인지 여부는 확인하지 않습니다. |
| [MakeConstRef](./makeconstref/) | [String](./string/)이거나 SmartPtr<> 타입인 경우 제네릭 타입을 "const reference"로 만드는 트레이트입니다. |
| [Math](./math/) | 수학 함수를 포함합니다. 이 타입은 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떤 방식으로도 인스턴스를 생성해서는 안 됩니다. |
| [MathF](./mathf/) | 단정밀 부동소수점 값을 위한 수학 함수를 포함합니다. 이 타입은 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떤 방식으로도 인스턴스를 생성해서는 안 됩니다. |
| [MethodArgumentTuple< R(*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | 메서드 인수를 저장하기 위한 튜플을 정의합니다. |
| [MethodArgumentTuple< R(C::*)(Args...) const >](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__const__end_tmpl/) | 메서드 인수를 저장하기 위한 튜플을 정의합니다. |
| [MethodArgumentTuple< R(C::*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | 메서드 인수를 저장하기 위한 튜플을 정의합니다. |
| [MulticastDelegateTypeInfo](./multicastdelegatetypeinfo/) | [TypeInfo](./typeinfo/) 객체에 대한 포인터를 나타내며, 해당 객체는 MulticastDelegate 클래스에 대한 정보를 포함합니다. |
| [RemoveShared](./removeshared/) | 인자 타입에서 SharedPtr/WeakPtr를 제거하기 위한 트레이트 구조체입니다. |
| [SByte](./sbyte/) | 8비트 정수를 다루는 메서드를 포함합니다. |
| [ScopeGuard](./scopeguard/) | 클래스 인스턴스가 범위를 벗어날 때 특정 함수 객체를 실행하는 서비스를 제공하는 서비스 클래스입니다. |
| [Single](./single/) | 단정밀 부동소수점 숫자를 다루는 메서드를 포함합니다. |
| [TestCompare](./testcompare/) | 컬렉션을 비교하기 위한 인터페이스를 제공하는 서비스 구조체입니다. |
| [TestTools](./testtools/) | 다양한 타입과 함수의 기본 속성을 확인하는 유용한 메서드 집합을 제공합니다. |
| [TestToolsExt](./testtoolsext/) | 테스트 번역에 사용되는 공통 함수입니다. |
| [TypeInfoPtr](./typeinfoptr/) | [TypeInfo](./typeinfo/) 클래스 인스턴스에 대한 포인터를 감싸는 래퍼입니다. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. [System::SmartPtr](./smartptr/) 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오. |
| [UInt16](./uint16/) | 부호 없는 16비트 정수를 다루는 메서드를 포함합니다. |
| [UInt32](./uint32/) | 부호 없는 32비트 정수를 다루는 메서드를 포함합니다. |
| [UInt64](./uint64/) | 부호 없는 64비트 정수를 다루는 메서드를 포함합니다. |
| [ValueTupleTypeInfo](./valuetupletypeinfo/) | [TypeInfo](./typeinfo/) 객체에 대한 포인터를 나타내며, 이 객체는 [ValueTuple](./valuetuple/) 클래스에 대한 정보를 포함합니다. |
| [WeakPtrFromTypeParameter](./weakptrfromtypeparameter/) | 인자 타입이 포인터 타입인 경우 약한 포인터로 변환하는 트레이트 구조체입니다. |

## 함수

| 함수 | 설명 |
| --- | --- |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(std::initializer_list\<T\>) | 새로운 [Array](./array/) 객체를 생성하고 지정된 초기화 리스트의 요소들로 채운 뒤, [Array](./array/) 객체를 가리키는 스마트 포인터를 반환하는 팩터리 함수입니다. |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(Args\&&...) | 지정된 인자를 생성자에 전달하여 새로운 [Array](./array/) 객체를 생성하는 팩터리 함수입니다. |
| std::enable_if\<std::is_integral\<Integral\>::value, [ArrayPtr](./arrayptr/)\<T\>\>::type [MakeArray](./makearray/)(Integral, Args\&&...) | 지정된 인수를 생성자에 전달하여 새로운 [Array](./array/) 객체를 생성하는 팩터리 함수입니다. |
| **bool** [operator==](./operator_equal_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) |  |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 지정된 [Nullable](./nullable/) 객체가 null과 같은 값을 나타내는지 여부를 판단합니다. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 지정된 값을 [operator==()](./operator_equal_equal/)를 적용하여 지정된 [Nullable](./nullable/) 객체가 나타내는 값과 같은지 여부를 판단합니다. |
| **bool** [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | 두 스마트 포인터를 동등 비교합니다. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | 스마트 포인터가 null인지 확인합니다. |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | 스마트 포인터와 일반 (C) 포인터를 동등 비교합니다. |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | 스마트 포인터와 일반 (C) 포인터를 동등 비교합니다. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(T const\&, std::nullptr_t) | 값 타입 객체(번역된 C# 구조체 등)가 null인지 확인합니다. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(std::nullptr_t, T const\&) | 값 타입 객체(번역된 C# 구조체 등)가 null인지 확인합니다. |
| **bool** [operator==](./operator_equal_equal/)(Chars\&, const [String](./string/)\&) | [String](./string/) 비교. |
| **bool** [operator==](./operator_equal_equal/)(T\&, const [String](./string/)\&) | [String](./string/) 비교. |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | [Object](./object/) 및 문자열 비교. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [String](./string/)\&) | 문자열이 null인지 확인합니다. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | 현재 및 지정된 객체가 나타내는 URI가 같은지 여부를 판단합니다. |
| **bool** [operator!=](./operator_not_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) |  |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 지정된 [Nullable](./nullable/) 객체가 null과 같지 않은 값을 나타내는지 여부를 판단합니다. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 지정된 값을 [operator!=()](./operator_not_equal/)를 적용하여 지정된 [Nullable](./nullable/) 객체가 나타내는 값과 같지 않은지 여부를 판단합니다. |
| **bool** [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | 두 스마트 포인터를 비동등 비교합니다. |
| **bool** [operator!=](./operator_not_equal/)([SmartPtr](./smartptr/)\<X\> const\&, std::nullptr_t) | 스마트 포인터가 null이 아닌지 확인합니다. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | 스마트 포인터가 null이 아닌지 확인합니다. |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | 스마트 포인터와 일반 (C) 포인터를 비동등 비교합니다. |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | 스마트 포인터와 일반 (C) 포인터를 동등 비교합니다. |
| **bool** [operator!=](./operator_not_equal/)(Chars\&, const [String](./string/)\&) | [String](./string/) 비교. |
| **bool** [operator!=](./operator_not_equal/)(T\&, const [String](./string/)\&) | [String](./string/) 비교. |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | [Object](./object/) 및 문자열 비교. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [String](./string/)\&) | 문자열이 null인지 확인합니다. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | 현재 및 지정된 객체가 나타내는 URI가 같지 않은지 여부를 판단합니다. |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) |  |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) |  |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) |  |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) |  |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator<](./operator_less/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 항상 false를 반환합니다. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 지정된 값을 [operator<()](./operator_less/)를 적용하여 지정된 [Nullable](./nullable/) 객체가 나타내는 값보다 작은지 여부를 판단합니다. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 항상 false를 반환합니다. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 지정된 값을 [operator<=()](./operator_less_equal/)를 적용하여 지정된 [Nullable](./nullable/) 객체가 나타내는 값보다 작거나 같은지 여부를 판단합니다. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator>](./operator_greater/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 항상 false를 반환합니다. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 지정된 값을 [operator>()](./operator_greater/)를 적용하여 지정된 [Nullable](./nullable/) 객체가 나타내는 값보다 큰지 여부를 판단합니다. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | 항상 false를 반환합니다. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | 지정된 값을 [operator>=()](./operator_greater_equal/)를 적용하여 지정된 [Nullable](./nullable/) 객체가 나타내는 값보다 크거나 같은지 여부를 판단합니다. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| void [PrintTo](./printto/)([DateTime](./datetime/), std::ostream *) | 값을 ostream에 출력합니다. 주로 디버그에 사용됩니다. |
| void [PrintTo](./printto/)([DateTimeOffset](./datetimeoffset/), std::ostream *) | 값을 ostream에 출력합니다. 주로 디버그에 사용됩니다. |
| void [PrintTo](./printto/)(const [Decimal](./decimal/)\&, ::std::ostream *) | 지정된 객체가 나타내는 값을 지정된 출력 스트림에 씁니다. |
| void [PrintTo](./printto/)(const [Details_Exception](./details_exception/)\&, std::ostream *) | 값을 ostream에 출력합니다. 주로 디버그에 사용됩니다. |
| void [PrintTo](./printto/)(const [ExceptionWrapper](./exceptionwrapper/)\<T\>\&, std::ostream *) | 값을 ostream에 출력합니다. 주로 디버그에 사용됩니다. |
| void [PrintTo](./printto/)(const [Guid](./guid/)\&, std::ostream *) | 값을 ostream에 출력합니다. 주로 디버그에 사용됩니다. |
| void [PrintTo](./printto/)(const [Nullable](./nullable/)\<T\>\&, std::ostream *) | 값을 ostream에 출력합니다. 주로 디버그에 사용됩니다. |
| void [PrintTo](./printto/)(const [System::Object](./object/)\&, std::ostream *) | 값을 ostream에 출력합니다. 주로 디버그에 사용됩니다. |
| std::enable_if_t\<detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | 값을 ostream에 출력합니다. 주로 디버그에 사용됩니다. |
| std::enable_if_t<\!detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | 값을 ostream에 출력합니다. 주로 디버그에 사용됩니다. |
| void [PrintTo](./printto/)(const [System::String](./string/)\&, std::ostream *) | 문자열을 ostream에 출력합니다. 주로 디버그에 사용됩니다. |
| void [PrintTo](./printto/)([TimeSpan](./timespan/), std::ostream *) | 값을 ostream에 출력합니다. 주로 디버그에 사용됩니다. |
| void [PrintTo](./printto/)(const [WeakPtr](./weakptr/)\<T\>\&, std::ostream *) | 값을 ostream에 출력합니다. 주로 디버그에 사용됩니다. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTime](./datetime/)) | UTF-8 인코딩을 사용하여 스트림에 데이터를 삽입합니다. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTime](./datetime/)) | 스트림에 데이터를 삽입합니다. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTimeOffset](./datetimeoffset/)) | UTF-8 인코딩을 사용하여 스트림에 데이터를 삽입합니다. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTimeOffset](./datetimeoffset/)) | 스트림에 데이터를 삽입합니다. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Decimal](./decimal/)\&) | UTF-8 인코딩을 사용하여 스트림에 데이터를 삽입합니다. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Decimal](./decimal/)\&) | 스트림에 데이터를 삽입합니다. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Exception](./exception/)\&) | UTF-8 인코딩을 사용하여 스트림에 데이터를 삽입합니다. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Exception](./exception/)\&) | 스트림에 데이터를 삽입합니다. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Guid](./guid/)\&) | UTF-8 인코딩을 사용하여 스트림에 데이터를 삽입합니다. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Guid](./guid/)\&) | 스트림에 데이터를 삽입합니다. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Nullable](./nullable/)\<T\>\&) | UTF-8 인코딩을 사용하여 스트림에 데이터를 삽입합니다. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Nullable](./nullable/)\<T\>\&) | 스트림에 데이터를 삽입합니다. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [System::Object](./object/)\&) | UTF-8 인코딩을 사용하여 스트림에 데이터를 삽입합니다. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [System::Object](./object/)\&) | 스트림에 데이터를 삽입합니다. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [OperatingSystem](./operatingsystem/)\&) | UTF-8 인코딩을 사용하여 스트림에 데이터를 삽입합니다. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [OperatingSystem](./operatingsystem/)\&) | 스트림에 데이터를 삽입합니다. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | UTF-8 인코딩을 사용하여 스트림에 데이터를 삽입합니다. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | 스트림에 데이터를 삽입합니다. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [String](./string/)\&) | UTF-8 인코딩을 사용하여 문자열을 출력 스트림에 출력합니다. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [String](./string/)\&) | 문자열을 출력 스트림에 출력합니다. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [TimeSpan](./timespan/)) | UTF-8 인코딩을 사용하여 스트림에 데이터를 삽입합니다. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [TimeSpan](./timespan/)) | 스트림에 데이터를 삽입합니다. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [TypeInfo](./typeinfo/)\&) | UTF-8 인코딩을 사용하여 스트림에 데이터를 삽입합니다. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [TypeInfo](./typeinfo/)\&) | 스트림에 데이터를 삽입합니다. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Version](./version/)\&) | UTF-8 인코딩을 사용하여 스트림에 데이터를 삽입합니다. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Version](./version/)\&) | 스트림에 데이터를 삽입합니다. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | UTF-8 인코딩을 사용하여 스트림에 데이터를 삽입합니다. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | 스트림에 데이터를 삽입합니다. |
| auto [operator-](./operator_minus/)([DayOfWeek](./dayofweek/), [DayOfWeek](./dayofweek/)) | 두 요일 사이의 일수 차이를 계산합니다. |
| [Decimal](./decimal/) [operator-](./operator_minus/)(const T\&, const [Decimal](./decimal/)\&) | [Decimal](./decimal/) 클래스의 새 인스턴스를 반환합니다. 이 인스턴스는 지정된 값에서 지정된 [Decimal](./decimal/) 객체가 나타내는 값을 빼서 얻은 결과 값을 나타냅니다. |
| MulticastDelegate\<T\> [operator-](./operator_minus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | 오른쪽 delegate의 모든 콜백을 왼쪽 delegate 콜백 목록의 끝에서 분리합니다. |
| auto [operator-](./operator_minus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | null이 아닌 값과 nullable 값을 빼습니다. |
| [Decimal](./decimal/) [operator+](./operator_plus/)(const T\&, const [Decimal](./decimal/)\&) | 지정된 값과 지정된 [Decimal](./decimal/) 객체가 나타내는 값의 합을 나타내는 [Decimal](./decimal/) 클래스의 새 인스턴스를 반환합니다. |
| MulticastDelegate\<T\> [operator+](./operator_plus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | 오른쪽 대리자의 모든 콜백을 왼쪽 대리자 콜백 리스트 끝에 연결합니다. |
| auto [operator+](./operator_plus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | null이 아닌 값과 nullable 값을 더합니다. |
| std::enable_if\<[IsStringLiteral](./isstringliteral/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) 연결. |
| std::enable_if\<[IsStringPointer](./isstringpointer/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) 연결. |
| [String](./string/) [operator+](./operator_plus/)(const char_t, const [String](./string/)\&) | [String](./string/) 연결. |
| [Decimal](./decimal/) [operator*](./operator_star/)(const T\&, const [Decimal](./decimal/)\&) | 지정된 값과 지정된 [Decimal](./decimal/) 객체가 나타내는 값의 곱 결과를 나타내는 [Decimal](./decimal/) 클래스의 새 인스턴스를 반환합니다. |
| [Decimal](./decimal/) [operator/](./operator_div/)(const T\&, const [Decimal](./decimal/)\&) | 지정된 값과 지정된 [Decimal](./decimal/) 객체가 나타내는 값의 나눗셈 결과를 나타내는 [Decimal](./decimal/) 클래스의 새 인스턴스를 반환합니다. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | 예외 유형의 단일 기본 생성 인스턴스에 대한 참조를 반환합니다. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | 비예외 유형의 단일 기본 생성 인스턴스에 대한 참조를 반환합니다. |
| T\& [Discard](./discard/)(T\&&) | 지정된 유형의 기본 생성된 임시 인스턴스를 반환하며, 이는 '_' 인수를 버리는 대신 사용할 수 있습니다. |
| Details::ObjectBuilder\<T, [SharedPtr](./sharedptr/)\<T\>\> [BuildObject](./buildobject/)(Args\&&...) | 공유 소유권을 가진 객체를 빌드합니다. |
| Details::ObjectBuilder\<T, [SharedPtr](./sharedptr/)\<T\>\> [InitObject](./initobject/)(const [SharedPtr](./sharedptr/)\<T\>\&) | 공유 소유권을 가진 객체의 초기화를 시작합니다. |
| Details::ObjectBuilder\<Details::ArrayStorage\<T\>\> [BuildArray](./buildarray/)() | 배열을 빌드합니다. |
| Details::ObjectBuilder\<T\> [Build](./build/)(Args\&&...) | 직접 소유권을 가진 객체를 빌드합니다. |
| **bool** [Is](./is/)(const ExpressionT\&, ResultT\&) | 'is' 선언 패턴 변환을 구현합니다. |
| std::enable_if_t<\!std::is_base_of\<Details::Pattern, ConstantT\>::value, **bool**\> [Is](./is/)(const ExpressionT\&, const ConstantT\&) | 'is' 상수 패턴 변환을 구현합니다. |
| std::enable_if_t\<std::is_base_of\<Details::Pattern, A\>::value, **bool**\> [Is](./is/)(const E\&, const A\&) | 최상위 매칭 함수. 패턴을 값에 적용합니다. |
| static **bool** [IsNull](./isnull/)(const T\&) | 'is null' 패턴을 구현합니다. |
| **bool** [Less](./less/)(const ExpressionT\&, const ConstantT\&) | '<' 상대 패턴 변환을 구현합니다. |
| **bool** [Greater](./greater/)(const ExpressionT\&, const ConstantT\&) | '>' 상대 패턴 변환을 구현합니다. |
| **bool** [LEqual](./lequal/)(const ExpressionT\&, const ConstantT\&) | '<=' 상대 패턴 변환을 구현합니다. |
| **bool** [GEqual](./gequal/)(const ExpressionT\&, const ConstantT\&) | '>=' 상대 패턴 변환을 구현합니다. |
| **bool** [Set](./set/)(ExpressionT\&, const ExpressionT\&) | 'var' 패턴 변환을 구현합니다. |
| **bool** [IsTuple](./istuple/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, **int32_t**) | 객체가 튜플인지 확인합니다(ITuple 인터페이스 구현). 위치 패턴 구현에 사용됩니다. |
| auto [Get](./get/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&) | 주어진 튜플의 N번째 요소를 가져오는 함수입니다. 기본 객체에 대한 오버로드입니다. |
| auto [Get](./get/)(const T\&) | 주어진 튜플의 N번째 요소를 가져오는 함수입니다. Deconstruct 메서드가 있는 객체에 대한 오버로드입니다. |
| auto [Get](./get/)(const [SharedPtr](./sharedptr/)\<T\>\&) | 주어진 튜플의 N번째 요소를 가져오는 함수입니다. 공유 포인터에 대한 오버로드입니다. |
| auto\& [Get](./get/)(T\&, const [Index](./index/)\&) | collection[index] 표현식에 대한 구현입니다. |
| auto [Get](./get/)(T\&, const [Range](./range/)\&) | 제공된 범위에 의해 정의된 지정된 컬렉션의 슬라이스를 반환합니다. |
| auto [Get](./get/)(const [ValueTuple](./valuetuple/)\<Args...\>\&) | 값 튜플의 N번째 요소를 가져옵니다. |
| [SharedPtr](./sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<T\>\> [MakeYieldEnumerable](./makeyieldenumerable/)(const Details::YieldFunction\<T\>\&) | yield 함수로부터 IEnumerable을 생성합니다. |
| [SharedPtr](./sharedptr/)\<[Collections::Generic::IEnumerator](../system.collections.generic/ienumerator/)\<T\>\> [MakeYieldEnumerator](./makeyieldenumerator/)(const Details::YieldFunction\<T\>\&) | yield 함수로부터 IEnumerator를 생성합니다. |
| std::enable_if_t\<Details::is_lambda_void_void\<T\>::value\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | C#의 try[-catch]-finally 문 동작을 에뮬레이트하는 단일 함수입니다. 번역기의 옵션 finally_statement_as_lambda가 true로 설정된 상태에서 C#의 try[-catch]-finally 문을 번역하면 해당 문이 이 메서드 호출로 변환됩니다. |
| std::enable_if_t\<Details::is_lambda_void_boolref\<T\>::value, **bool**\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | C#의 try[-catch]-finally 문 동작을 에뮬레이트하는 단일 함수입니다. 번역기의 옵션 finally_statement_as_lambda가 true로 설정된 상태에서 C#의 try[-catch]-finally 문을 번역하면 해당 문이 이 메서드 호출로 변환됩니다. 이 오버로드는 try[-catch]-finally 문에서 try[-catch] 부분을 구현하는 함수 객체의 반환 값이 bool인 경우를 처리합니다. |
| std::enable_if_t\<Details::is_lambda_nonovoid_boolref\<T\>::value, std::optional\<Details::ResultOf\<T, **bool**\&\>\>\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | C#의 try[-catch]-finally 문 동작을 에뮬레이트하는 단일 함수입니다. 번역기의 옵션 finally_statement_as_lambda가 true로 설정된 상태에서 C#의 try[-catch]-finally 문을 번역하면 해당 문이 이 메서드 호출로 변환됩니다. 이 오버로드는 try[-catch]-finally 문에서 try[-catch] 부분을 구현하는 함수 객체의 반환 값이 bool&인 경우를 처리합니다. |
| [DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>::Reference [Ref](./ref/)([DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\&) | [DynamicWeakPtr](./dynamicweakptr/) 객체에 대한 참조를 생성합니다. 번역기가 함수 인수를 참조로 전달할 때 사용됩니다. |
| T\& [Ref](./ref/)(T\&) | 객체에 대한 참조를 얻는 도우미 함수입니다. 할당 후 [System::DynamicWeakPtr](./dynamicweakptr/)이 참조된 객체를 업데이트하도록 보장하는 데 사용됩니다. |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | 이 함수 속성은 enumerable(또는 iterable) 객체를 래핑하여 range-based for 루프에서 사용할 수 있게 합니다. 이 오버로드는 begin(), end() 메서드가 없는 Enumerable에 대해 target type 인자를 사용하여 (auto& value : IterateOver<SomeType>(enumerable)) 형태로 사용할 수 있습니다. |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | 이 함수 속성은 enumerable(또는 iterable) 객체를 래핑하여 range-based for 루프에서 사용할 수 있게 합니다. 이 오버로드는 begin(), end() 메서드가 없는 Enumerable에 대해 기본 target type 인자를 사용하여 (auto& value : IterateOver(enumerable)) 형태로 사용할 수 있으며, 다음 C# 코드 foreach (var value in enumerable)와 유사합니다. |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | 이 함수 속성은 enumerable(또는 iterable) 객체를 래핑하여 range-based for 루프에서 사용할 수 있게 합니다. 이 오버로드는 begin(), end() 메서드가 있는 Enumerable에 대해 기본 target type 인자를 사용하여 (auto& value : IterateOver(enumerable)) 형태로 사용할 수 있습니다. |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | 이 함수 속성은 enumerable(또는 iterable) 객체를 래핑하여 range-based for 루프에서 사용할 수 있게 합니다. 이 오버로드는 begin(), end() 메서드가 있는 Enumerable에 대해 target type이 iterator의 원래 value_type과 동일한 경우에 사용됩니다. |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&\!std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, Details::CppIteratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | 이 함수 속성은 enumerable(또는 iterable) 객체를 래핑하여 range-based for 루프에서 사용할 수 있게 합니다. 이 오버로드는 begin(), end() 메서드가 있는 Enumerable에 대해 target type이 원래 iterator의 value_type과 다른 경우에 사용됩니다. |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, Details::ValueTypeOfEnumerable\<Enumerable\>, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | 이 함수 속성은 enumerable(또는 iterable) 객체를 래핑하여 range-based for 루프에서 사용할 수 있게 합니다. 이 오버로드는 기본 target type을 사용하는 Enumerable this에 대해 적용됩니다. |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | 이 함수 속성은 enumerable(또는 iterable) 객체를 래핑하여 range-based for 루프에서 사용할 수 있게 합니다. 이 오버로드는 begin(), end() 메서드가 없는 Enumerable에 대해 target type 인자를 사용하여 (auto& value : IterateOver<SomeType>(enumerable)) 형태로 사용할 수 있습니다. |
| std::enable_if\<std::is_scalar\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | 지정된 스칼라 값에 대한 해시 코드를 반환합니다. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&[System::IsSmartPtr](./issmartptr/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | 지정된 객체에 대한 해시 코드를 반환합니다. |
| std::enable_if\<[System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | 예외인 지정된 객체에 대한 해시 코드를 반환합니다. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\![System::IsSmartPtr](./issmartptr/)\<T\>::value\&&\![System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | 스마트 포인터도 아니고 예외도 아닌 지정된 객체에 대한 해시 코드를 반환합니다. |
| int [GetHashCode](./gethashcode/)(const std::thread::id\&) | std::thread::id에 대한 특수화; 지정된 스레드 객체에 대한 해시 코드를 반환합니다. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast_noexcept](./cast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | [SmartPtr](./smartptr/) 객체에 대해 캐스트를 수행합니다. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast](./cast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | [SmartPtr](./smartptr/) 객체에 대해 캐스트를 수행합니다. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)(const TFrom\&) | 오래된 사용되지 않는 캐스트입니다. 향후 버전에서 제거될 예정입니다. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | [SmartPtr](./smartptr/) 객체에 대해 동적 캐스트를 수행합니다. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | Object를 Exception 객체로 동적 캐스트합니다. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast](./dynamiccast/)(const TFrom\&) | Exception 객체에 대해 동적 캐스트를 수행합니다. |
| std::enable_if<\!std::is_enum\<TTo\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | [SmartPtr](./smartptr/) 객체에 대해 동적 캐스트를 수행합니다. |
| std::enable_if\<std::is_enum\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | 캐스트를 통해 박싱된 enum을 언박싱합니다. |
| [CastResult](./castresult/)\<TTo\>::type [DynamicCast](./dynamiccast/)(std::nullptr_t) | null 객체에 대해 동적 캐스트를 수행합니다. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&std::is_convertible\<TTo, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom\&) | 포인터가 아닌 객체에 대해 동적 캐스트를 수행합니다. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | Objects를 Exception 객체로 동적 캐스트를 수행합니다. |
| std::enable_if\<std::is_pointer\<TTo\>::value\&&std::is_same\<IntPtr, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom) | IntPtr에서 포인터로 동적 캐스트를 수행합니다. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | [SmartPtr](./smartptr/) 객체에 static 캐스트를 수행합니다. |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | [WeakPtr](./weakptr/) 객체에 static 캐스트를 수행합니다. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)(const TFrom\&) | Exception 객체에 static 캐스트를 수행합니다. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | Objects를 Exception 객체로 static 캐스트를 수행합니다. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | [SmartPtr](./smartptr/) 객체에 static 캐스트를 수행합니다. |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | [WeakPtr](./weakptr/) 객체에 static 캐스트를 수행합니다. |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)(std::nullptr_t) | null 객체에 static 캐스트를 수행합니다. |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(TFrom) | 산술형에 대한 특수화. |
| std::enable_if\<std::is_same\<TTo, [System::String](./string/)\>::value, TTo\>::type [StaticCast](./staticcast/)(TTo) | [String](./string/)에서 [String](./string/) 로 캐스트를 처리합니다. |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom *) | 산술형에 대한 특수화. |
| std::enable_if<\!std::is_same\<TFrom, [System::String](./string/)\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&\!std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | 포인터가 아닌 객체에 static 캐스트를 수행합니다. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | Exception 객체에 static 캐스트를 수행합니다. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\>) | Objects를 Exception 객체로 static 캐스트를 수행합니다. |
| [CastResult](./castresult/)\<TTo\>::type [ConstCast](./constcast/)(const [SmartPtr](./smartptr/)\<TFrom\>\&) | 폐기된 캐스트의 종료. |
| [CastResult](./castresult/)\<TTo\>::type [ForceStaticCast](./forcestaticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | [SmartPtr](./smartptr/) 객체에 실제 static 캐스트를 수행합니다. |
| [SmartPtr](./smartptr/)\<[Object](./object/)\> [MemberwiseClone](./memberwiseclone/)(T *) | 복사 생성자를 사용하여 멤버별 복제를 수행합니다. |
| [SharedPtr](./sharedptr/)\<T\> [With](./with/)(const [SharedPtr](./sharedptr/)\<T\>\&, const A\&) | 레코드 참조를 복제하고 초기화 함수를 적용합니다. |
| T [With](./with/)(const T\&, const A\&) | 구조체 레코드를 복제하고 초기화 함수를 적용합니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 명시적 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 소스와 결과 유형이 동일할 때 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 명시적 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 간단한 생성자와 같은 캐스트가 필요할 때 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 명시적 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 예외 래퍼에 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 명시적 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 객체를 예외로 캐스트할 때 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 명시적 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 소스와 결과가 모두 스마트 포인터인 경우에 사용됩니다 (결과 유형에 명시적인 SmartPtr<...>가 없는 경우). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::RawPointer, typename [CastResult](./castresult/)\<std::remove_pointer_t\<Result\>\>::type\> [ExplicitCast](./explicitcast/)(Source) | 명시적 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 원시 포인터를 스마트 포인터로 캐스트할 때 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 명시적 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 소스와 결과가 모두 스마트 포인터인 경우에 사용됩니다 (결과 유형에 명시적인 SmartPtr<...>가 있는 경우). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 명시적 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 객체를 nullable로 언박싱할 때 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | nullable을 박싱할 때 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableUnboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 명시적 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. nullable 객체를 언박싱할 때 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::EnumBoxing, [SmartPtr](./smartptr/)\<[BoxedValueBase](./boxedvaluebase/)\>\> [ExplicitCast](./explicitcast/)(const Source\&) | 명시적 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. enum을 박싱할 때 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::HeapifyBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 값 형식을 힙에 복사하는 데 사용됩니다. 값 형식이 스마트 포인터로 참조되어야 할 때(인터페이스 타입으로 제한된 제네릭이지만 해당 인터페이스를 구현하는 구조체로 특수화된 경우). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 값 형식에서 인터페이스를 가져오는 데 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 일반 박싱에 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::StringBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | [System::String](./string/) 박싱에 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceUnboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 인터페이스를 언박싱하는 데 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Unboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | 일반 언박싱에 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | nullptr 캐스팅에 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | 배열 간 캐스팅에 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 연산자 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 간단한 생성자와 같은 캐스트가 필요할 때 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 연산자 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 소스와 결과 유형이 동일할 때 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [AsCast](./ascast/)(const Source\&) | 'as' 연산자 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 예외 래퍼에 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 연산자 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 객체를 예외로 캐스트할 때 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 'as' 연산자 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 소스와 결과가 모두 스마트 포인터인 경우에 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 연산자 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 소스와 결과가 모두 스마트 포인터인 경우에 사용됩니다 (결과 유형에 명시적인 SmartPtr<...>가 있는 경우). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 연산자 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 객체를 nullable로 언박싱할 때 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceUnboxingToNullable, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 연산자 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 비객체 유형에 대한 잘못된 언박싱. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InvalidUnboxing, Result\> [AsCast](./ascast/)(const Source\&) | 비객체 유형에 대한 잘못된 언박싱. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 연산자 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. nullable 객체를 박싱할 때 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 'as' 연산자 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 일반 객체를 박싱할 때 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 'as' 연산자 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 일반 객체를 박싱할 때 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToString, Result\> [AsCast](./ascast/)(const Source\&) | 'as' 연산자 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 문자열 언박싱에 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 'as' 연산자 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. nullptr 케이스에 사용됩니다. |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | 'as' 연산자 캐스트를 사용하여 소스 유형을 결과 유형으로 변환합니다. 배열 간 캐스팅에 사용됩니다. |
| static auto [SafeInvoke](./safeinvoke/)(T0\&&, T1\&&) | '?.' 연산자 변환 구현. |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::String >](./objecttype_dcolon_gettype_less_system_dcolon_string__greater/)() | typeof() 변환을 구현합니다. [String](./string/)에 대한 오버로드. |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::DateTime >](./objecttype_dcolon_gettype_less_system_dcolon_datetime__greater/)() | typeof() 변환을 구현합니다. [DateTime](./datetime/)에 대한 오버로드. |
| **bool** [Equals](./equals/)(const TA\&, const TB\&) | 두 값에 [operator==()](./operator_equal_equal/)을 적용하여 동등성을 판단합니다. |
| **bool** [Equals< float, float >](./equals_less_float,_float__greater/)(const **float**\&, const **float**\&) | 단정도 부동소수점 값에 대한 특수화입니다. IEC 60559:1989에 따르면 두 부동소수점 NaN은 항상 서로 다르다고 비교되지만, [System.Object.Equals](./object/equals/)에 대한 계약은 오버라이드가 동일성 연산자 요구사항을 만족해야 함을 요구합니다. 따라서 System.Double.Equals와 System.Single.Equals는 두 NaN을 비교할 때 True를 반환하고, 동일성 연산자는 해당 경우 False를 반환합니다(표준이 요구하는 바와 같습니다). |
| **bool** [Equals< double, double >](./equals_less_double,_double__greater/)(const **double**\&, const **double**\&) | 배정도 부동소수점 값에 대한 특수화. |
| std::enable_if_t<\!std::is_floating_point\<TA\>::value\&&\!std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | 두 값을 비교합니다. |
| std::enable_if_t\<std::is_floating_point\<TA\>::value\&&std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | 두 부동 소수점 값을 비교합니다. |
| **bool** [IsNaN](./isnan/)(const T\&) | 지정된 값이 Not-A-Number 값인지 여부를 결정합니다. |
| **bool** [IsInfinity](./isinfinity/)(const T\&) | 지정된 값이 무한대를 나타내는지 여부를 결정합니다. |
| **bool** [IsPositiveInfinity](./ispositiveinfinity/)(const T\&) | 지정된 값이 양의 무한대를 나타내는지 여부를 결정합니다. |
| **bool** [IsNegativeInfinity](./isnegativeinfinity/)(const T\&) | 지정된 값이 음의 무한대를 나타내는지 여부를 결정합니다. |
| TTo [CheckedCast](./checkedcast/)(TFrom) | 지정된 값이 **TTo** 형식의 값 범위에 포함되는지 여부를 결정하고, 포함될 경우 **TTo** 형식으로 캐스팅합니다. |
| [ScopeGuard](./scopeguard/)\<F\> [MakeScopeGuard](./makescopeguard/)(F) | ScopedGuard 클래스를 인스턴스화하는 팩터리 함수입니다. |
| T [setter_wrap](./setter_wrap/)(void(*)(T2), T) | 형 변환을 포함하는 정적 세터 함수에 대한 오버로드입니다. |
| std::enable_if\<std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_wrap](./setter_wrap/)(Host *const, void(HostSet::*)(T2), T) | 형 변환을 포함하는 인스턴스 세터 함수에 대한 오버로드입니다. |
| T [setter_increment_wrap](./setter_increment_wrap/)(T(*)(), void(*)(T)) | 번역기는 셋터와 게터가 정의된 클래스의 속성을 대상으로 하는 C#의 증감 연산자를 이 함수 호출로 변환합니다. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_increment_wrap](./setter_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | 번역기는 셋터와 게터가 정의된 클래스의 속성을 대상으로 하는 C#의 증감 연산자를 이 함수 호출로 변환합니다. |
| T [setter_post_increment_wrap](./setter_post_increment_wrap/)(T(*)(), void(*)(T)) | 번역기는 셋터와 게터가 정의된 클래스의 속성을 대상으로 하는 C#의 후위 증감 연산자를 이 함수 호출로 변환합니다. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | 번역기는 셋터와 게터가 정의된 인스턴스의 속성을 대상으로 하는 C#의 후위 증감 연산자를 이 함수 호출로 변환합니다(비-const 게터용 오버로드). |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | 번역기는 셋터와 게터가 정의된 인스턴스의 속성을 대상으로 하는 C#의 후위 증감 연산자를 이 함수 호출로 변환합니다(const 게터용 오버로드). |
| T [setter_decrement_wrap](./setter_decrement_wrap/)(T(*)(), void(*)(T)) | 번역기는 셋터와 게터가 정의된 클래스의 속성을 대상으로 하는 C#의 전위 감소 연산자를 이 함수 호출로 변환합니다. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | 번역기는 셋터와 게터가 정의된 인스턴스의 속성을 대상으로 하는 C#의 전위 감소 연산자를 이 함수 호출로 변환합니다(비-const 게터용 오버로드). |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | 번역기는 셋터와 게터가 정의된 인스턴스의 속성을 대상으로 하는 C#의 전위 감소 연산자를 이 함수 호출로 변환합니다(const 게터용 오버로드). |
| T [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(T(*)(), void(*)(T)) | 번역기는 셋터와 게터가 정의된 클래스의 속성을 대상으로 하는 C#의 후위 감소 연산자를 이 함수 호출로 변환합니다. |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | 번역기는 셋터와 게터가 정의된 인스턴스의 속성을 대상으로 하는 C#의 후위 감소 연산자를 이 함수 호출로 변환합니다(비-const 게터용 오버로드). |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | 번역기는 셋터와 게터가 정의된 인스턴스의 속성을 대상으로 하는 C#의 후위 감소 연산자를 이 함수 호출로 변환합니다(const 게터용 오버로드). |
| std::enable_if<\![IsSmartPtr](./issmartptr/)\<T\>::value, [SmartPtr](./smartptr/)\<T\>\>::type [MakeObject](./makeobject/)(Args\&&...) | 힙에 객체를 생성하고 해당 객체에 대한 shared pointer를 반환합니다. |
| std::enable_if\<[IsSmartPtr](./issmartptr/)\<T\>::value, T\>::type [MakeObject](./makeobject/)(Args\&&...) | 힙에 객체를 생성하고 해당 객체에 대한 shared pointer를 반환합니다. |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(X *) | 원시 포인터를 스마트 포인터로 변환합니다. |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(const X *) | 원시 포인터를 스마트 포인터로 변환합니다. const 포인터에 대한 오버로드입니다. 예를 들어 const로 번역된 C# 메서드에서 'this' 변수를 사용할 때 유용합니다. |
| [SmartPtr](./smartptr/)\<Y\> [static_pointer_cast](./static_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | static_cast를 사용하여 스마트 포인터를 캐스팅합니다. |
| [SmartPtr](./smartptr/)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | dynamic_cast를 사용하여 스마트 포인터를 캐스팅합니다. |
| [SmartPtr](./smartptr/)\<Y\> [const_pointer_cast](./const_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | const_cast를 사용하여 스마트 포인터를 캐스팅합니다. |
| T * [get_pointer](./get_pointer/)([System::SmartPtr](./smartptr/)\<T\> const\&) | 스마트 포인터가 참조하는 객체를 가져옵니다. |
| std::enable_if<\!System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | 지정된 열거형 객체의 요소들을 다른 형식으로 명시적 캐스팅합니다. |
| std::enable_if\<System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | 지정된 열거형 객체의 요소들을 다른 형식으로 명시적 캐스팅합니다. |
| std::enable_if_t\<[System::IsSmartPtr](./issmartptr/)\<From\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | 지정된 배열의 요소들을 다른 형식으로 캐스팅합니다. From이 [SmartPtr](./smartptr/) 객체인 경우에 대한 재정의입니다. |
| std::enable_if_t<\![System::IsSmartPtr](./issmartptr/)\<From\>::value\&&[System::IsBoxable](./isboxable/)\<From\>::value\&&std::is_same\<To, [System::SharedPtr](./sharedptr/)\<[Object](./object/)\>\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | 지정된 배열의 요소들을 다른 형식으로 캐스팅합니다. From이 Boxable이고 To가 [Object](./object/)[]인 경우에 대한 재정의입니다. |
| [SharedPtr](./sharedptr/)\<[Array](./array/)\<To\>\> [DynamicCastArray](./dynamiccastarray/)(const [SharedPtr](./sharedptr/)\<[Array](./array/)\<From\>\>\&) | 지정된 배열의 요소들을 다른 형식으로 캐스팅합니다. |
| std::istream\& [operator>>](./operator_greater_greater/)(std::istream\&, [String](./string/)\&) | UTF-8 인코딩을 사용하여 입력 스트림에서 문자열을 가져옵니다. |
| std::wistream\& [operator>>](./operator_greater_greater/)(std::wistream\&, [String](./string/)\&) | 입력 스트림에서 문자열을 가져옵니다. |
| [TaskPtr](./taskptr/) [MakeAsync](./makeasync/)(const Details::AsyncFunction\&) |  |
| [RTaskPtr](./rtaskptr/)\<T\> [MakeAsync](./makeasync/)(const Details::ResultAsyncFunction\<T\>\&) |  |
| [Threading::Tasks::ResultValueTask](../system.threading.tasks/resultvaluetask/)\<T\> [MakeValueAsync](./makevalueasync/)(const Details::ResultAsyncFunction\<T\>\&) |  |
| [Threading::Tasks::ValueTask](../system.threading.tasks/valuetask/) [MakeValueAsync](./makevalueasync/)(const Details::AsyncFunction\&) |  |
| [ValueTuple](./valuetuple/)\<Args...\> [MakeTuple](./maketuple/)(Args...) | 튜플을 스택에 생성합니다. |
| [ValueTuple](./valuetuple/)\<Args...\> [TieTuple](./tietuple/)(Args\&&...) | 값에 바인딩된 튜플을 생성합니다. |
| **bool** [is_vp_test](./is_vp_test/)(const ::testing::TestInfo *) |  |
| **bool** [is_parametrized_test](./is_parametrized_test/)(const ::testing::TestInfo *) |  |
| std::string [ForEachMemberGVName](./foreachmembergvname/)() |  |

## 열거형

| 열거형 | 설명 |
| --- | --- |
| [Base64FormattingOptions](./base64formattingoptions/) | Base-64 인코딩 데이터의 다양한 형식을 나타내는 값을 포함하는 열거형입니다. |
| [DateTimeKind](./datetimekind/) | 날짜와 시간의 종류를 나타내는 열거형 값입니다. |
| [DayOfWeek](./dayofweek/) | 요일을 나타내는 열거형입니다. |
| [EnvironmentVariableTarget](./environmentvariabletarget/) | 환경 변수 위치를 지정합니다. |
| [MidpointRounding](./midpointrounding/) | 반올림 함수의 동작을 지정합니다. |
| [PlatformID](./platformid/) | 운영 체제 플랫폼을 나타냅니다. |
| [SmartPtrMode](./smartptrmode/) | [SmartPtr](./smartptr/) 포인터 유형: weak 또는 shared. 객체 삭제 여부를 결정할 때 포인터가 카운트되는지를 정의합니다. |
| [StringSplitOptions](./stringsplitoptions/) | 문자열 분할 동작을 결정합니다. |
| [StringComparison](./stringcomparison/) | 문자열 비교 방식을 정의합니다. |
| [TypeCode](./typecode/) | 객체의 유형을 나타냅니다. |
| [UriKind](./urikind/) | URI 종류를 나타냅니다. |
| [UriComponents](./uricomponents/) | URI 구성 요소를 나타냅니다. |
| [UriFormat](./uriformat/) | URI가 어떻게 이스케이프되는지를 지정합니다. |
| [UriHostNameType](./urihostnametype/) | 호스트 이름의 유형을 나타냅니다. |
| [UriPartial](./uripartial/) | [Uri.GetLeftPart](./uri/getleftpart/) 메서드에 대한 URI의 부분을 나타냅니다. |

## 타입 별칭

| 타입 별칭 | 설명 |
| --- | --- |
| [IFormatProviderPtr](./iformatproviderptr/) | [System::IFormatProvider](./iformatprovider/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [DecoderFallbackPtr](./decoderfallbackptr/) | [System::Text::DecoderFallback](../system.text/decoderfallback/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [DecoderFallbackBufferPtr](./decoderfallbackbufferptr/) | [System::Text::DecoderFallbackBuffer](../system.text/decoderfallbackbuffer/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [DecoderReplacementFallbackPtr](./decoderreplacementfallbackptr/) | [System::Text::DecoderReplacementFallback](../system.text/decoderreplacementfallback/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [EncoderFallbackPtr](./encoderfallbackptr/) | [System::Text::EncoderFallback](../system.text/encoderfallback/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [EncoderFallbackBufferPtr](./encoderfallbackbufferptr/) | [System::Text::EncoderFallbackBuffer](../system.text/encoderfallbackbuffer/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [EncoderPtr](./encoderptr/) | [System::Text::Encoder](../system.text/encoder/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [DecoderPtr](./decoderptr/) | [System::Text::Decoder](../system.text/decoder/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [EncoderReplacementFallbackBufferPtr](./encoderreplacementfallbackbufferptr/) | [System::Text::EncoderReplacementFallbackBuffer](../system.text/encoderreplacementfallbackbuffer/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [EncoderReplacementFallbackPtr](./encoderreplacementfallbackptr/) | [System::Text::EncoderReplacementFallback](../system.text/encoderreplacementfallback/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [EncodingPtr](./encodingptr/) | [System::Text::Encoding](../system.text/encoding/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [EncodingInfoPtr](./encodinginfoptr/) | [System::Text::EncodingInfo](../system.text/encodinginfo/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [StreamPtr](./streamptr/) | [System::IO::Stream](../system.io/stream/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [FileStreamPtr](./filestreamptr/) | [System::IO::FileStream](../system.io/filestream/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [MemoryStreamPtr](./memorystreamptr/) | [System::IO::MemoryStream](../system.io/memorystream/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [StreamReaderPtr](./streamreaderptr/) | [System::IO::StreamReader](../system.io/streamreader/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [StreamWriterPtr](./streamwriterptr/) | [System::IO::StreamWriter](../system.io/streamwriter/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [FileInfoPtr](./fileinfoptr/) | [System::IO::FileInfo](../system.io/fileinfo/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [FileSystemInfoPtr](./filesysteminfoptr/) | [System::IO::FileSystemInfo](../system.io/filesysteminfo/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [DirectoryInfoPtr](./directoryinfoptr/) | [System::IO::DirectoryInfo](../system.io/directoryinfo/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [TaskPtr](./taskptr/) | [System::Threading::Tasks::Task](../system.threading.tasks/task/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [RTaskPtr](./rtaskptr/) | [System::Threading::Tasks::ResultTask](../system.threading.tasks/resulttask/) 클래스 인스턴스를 가리키는 스마트 포인터에 대한 별칭입니다. |
| [FunctionPtr](./functionptr/) | 기본 호출 규약을 가진 함수 타입에 대한 별칭입니다. |
| [Action](./action/) | 반환값이 없는 메서드를 참조하는 대리자 유형입니다. |
| [AggregateException](./aggregateexception/) |  |
| [ByteArrayPtr](./bytearrayptr/) | 부호 없는 8비트 정수 배열을 가리키는 스마트 포인터 객체에 대한 별칭입니다. |
| [AsyncCallback](./asynccallback/) | 비동기 작업이 완료될 때 호출되는 메서드를 나타내는 대리자 유형입니다. |
| [BadImageFormatException](./badimageformatexception/) | 동적 연결 라이브러리(DLL) 또는 실행 파일 이미지가 잘못된 경우 발생하는 예외입니다. BadImageFormatException 클래스 인스턴스를 [System::SmartPtr](./smartptr/)에 래핑하지 마세요. |
| [Converter](./converter/) | **TInput** 유형의 단일 인수를 받아 **TOutput** 유형의 값을 반환하는 호출 가능한 엔티티에 대한 포인터를 나타냅니다. |
| [Event](./event/) | 구독자가 관심 있는 이벤트 발생을 대리자 호출을 통해 통보받는 메커니즘인 이벤트를 나타냅니다. |
| [EventArgsPtr](./eventargsptr/) | [EventArgs](./eventargs/) 클래스 인스턴스에 대한 shared pointer입니다. |
| [EventHandler](./eventhandler/) | 이벤트에 반응하고 처리하는 메서드를 나타냅니다. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. 이 타입의 객체를 관리하기 위해 [System::SmartPtr](./smartptr/) 클래스를 사용하지 마세요. |
| [ExceptionPtr](./exceptionptr/) | 예외 래퍼에서 사용되는 타입 별칭입니다. |
| [Exception](./exception/) | Details::Exception 대신 사용할 별칭입니다. |
| [SystemException](./systemexception/) |  |
| [ApplicationException](./applicationexception/) |  |
| [InvalidOperationException](./invalidoperationexception/) |  |
| [InvalidProgramException](./invalidprogramexception/) |  |
| [InvalidTimeZoneException](./invalidtimezoneexception/) |  |
| [TimeZoneNotFoundException](./timezonenotfoundexception/) |  |
| [ObjectDisposedException](./objectdisposedexception/) |  |
| [NotImplementedException](./notimplementedexception/) |  |
| [NotSupportedException](./notsupportedexception/) |  |
| [PlatformNotSupportedException](./platformnotsupportedexception/) |  |
| [ArgumentException](./argumentexception/) |  |
| [ArgumentNullException](./argumentnullexception/) |  |
| [ArgumentOutOfRangeException](./argumentoutofrangeexception/) |  |
| [FormatException](./formatexception/) |  |
| [UriFormatException](./uriformatexception/) |  |
| [ArithmeticException](./arithmeticexception/) |  |
| [OverflowException](./overflowexception/) |  |
| [DivideByZeroException](./dividebyzeroexception/) |  |
| [OutOfMemoryException](./outofmemoryexception/) |  |
| [IndexOutOfRangeException](./indexoutofrangeexception/) |  |
| [RankException](./rankexception/) |  |
| [InvalidCastException](./invalidcastexception/) |  |
| [NullReferenceException](./nullreferenceexception/) |  |
| [UnauthorizedAccessException](./unauthorizedaccessexception/) |  |
| [MemberAccessException](./memberaccessexception/) |  |
| [MethodAccessException](./methodaccessexception/) |  |
| [OperationCanceledException](./operationcanceledexception/) |  |
| [StackOverflowException](./stackoverflowexception/) |  |
| [TimeoutException](./timeoutexception/) |  |
| [ExecutionEngineException](./executionengineexception/) |  |
| [TypeInitializationException](./typeinitializationexception/) |  |
| [DataMisalignedException](./datamisalignedexception/) |  |
| [IAsyncResultPtr](./iasyncresultptr/) | [IAsyncResult](./iasyncresult/)에 대한 공유 포인터입니다. |
| [MakeConstRef_t](./makeconstref_t/) | [MakeConstRef](./makeconstref/) 수정자를 위한 보조 타입입니다. |
| [Predicate](./predicate/) | 단일 인자를 받아 bool 값을 반환하는 호출 가능한 엔터티인 predicate에 대한 포인터를 나타냅니다. |
| [ArrayPtr](./arrayptr/) | 'pointer to array' 유형에 대한 별칭입니다. |
| [SharedPtr](./sharedptr/) | 라이브러리에서 널리 사용되는 스마트 포인터에 대한 별칭입니다. |
| [StringComparerPtr](./stringcomparerptr/) | [StringComparer](./stringcomparer/) 클래스의 인스턴스에 대한 공유 포인터 별칭입니다. |
| [TimeZonePtr](./timezoneptr/) | [TimeZone](./timezone/) 클래스의 인스턴스에 대한 공유 포인터입니다. |
| [TimeZoneInfoPtr](./timezoneinfoptr/) | [TimeZoneInfo](./timezoneinfo/) 클래스의 인스턴스에 대한 공유 포인터 별칭입니다. |