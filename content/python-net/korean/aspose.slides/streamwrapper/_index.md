---
title: StreamWrapper class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/streamwrapper/
---
## StreamWrapper 클래스

COM 인터페이스용 Aspose.IO.Stream 래퍼.

StreamWrapper 유형은 다음 멤버를 제공합니다:

## 속성

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/ko/aspose.slides/streamwrapper/stream/) | 스트림을 가져옵니다.<br/>            읽기 전용 **io.RawIOBase**. |
| [`can_read`](/slides/python-net/ko/aspose.slides/streamwrapper/can_read/) | 현재 스트림이 읽기를 지원하는지 여부를 나타내는 값을 가져옵니다.<br/>            읽기 전용 **bool**. |
| [`can_seek`](/slides/python-net/ko/aspose.slides/streamwrapper/can_seek/) | 현재 스트림이 탐색을 지원하는지 여부를 나타내는 값을 가져옵니다.<br/>            읽기 전용 **bool**. |
| [`can_write`](/slides/python-net/ko/aspose.slides/streamwrapper/can_write/) | 현재 스트림이 쓰기를 지원하는지 여부를 나타내는 값을 가져옵니다.<br/>            읽기 전용 **bool**. |
| [`length`](/slides/python-net/ko/aspose.slides/streamwrapper/length/) | 스트림의 바이트 길이를 가져옵니다.<br/>            읽기 전용 **int**. |
| [`position`](/slides/python-net/ko/aspose.slides/streamwrapper/position/) | 현재 스트림 내 위치를 가져오거나 설정합니다.<br/>            읽기 전용 **int**. |

## 메서드

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/ko/aspose.slides/streamwrapper/close/#) | 현재 스트림을 닫고 모든 리소스를 해제합니다. |
| [`flush(self)`](/slides/python-net/ko/aspose.slides/streamwrapper/flush/#) | 이 스트림의 모든 버퍼를 지우고 버퍼링된 데이터를 기본 장치에 기록하도록 합니다. |
| [`read(self, buffer, offset, count)`](/slides/python-net/ko/aspose.slides/streamwrapper/read/#bytes-int-int) | 현재 스트림에서 바이트 시퀀스를 읽고, 읽은 바이트 수만큼 스트림 내 위치를 전진시킵니다. |
| [`read_byte(self)`](/slides/python-net/ko/aspose.slides/streamwrapper/read_byte/#) | 스트림에서 한 바이트를 읽고 스트림 내 위치를 한 바이트 전진시키며, 스트림 끝에 도달하면 -1을 반환합니다. |
| [`seek(self, offset, origin)`](/slides/python-net/ko/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | 현재 스트림 내 위치를 설정합니다 |
| [`write(self, buffer, offset, count)`](/slides/python-net/ko/aspose.slides/streamwrapper/write/#bytes-int-int) | 현재 스트림에 바이트 시퀀스를 기록하고 기록한 바이트 수만큼 현재 위치를 전진시킵니다. |
| [`write_byte(self, value)`](/slides/python-net/ko/aspose.slides/streamwrapper/write_byte/#int) | 스트림의 현재 위치에 바이트를 기록하고 스트림 내 위치를 한 바이트 전진시킵니다. |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)