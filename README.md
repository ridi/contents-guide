# 리디북스 콘텐츠 제작 가이드

이 문서는.
- 리디북스 뷰어에서 콘텐츠를 최적의 상태로 제공할 수 있는 방법을 제시합니다.
- 리디북스 뷰어의 스펙을 플랫폼 별로 안내합니다.

## 목차

- [EPUB 제작 가이드](guide/epub.md)
  - [서문](guide/epub.md#preface)
    - [안내](guide/epub.md#foreword)
    - [참고](guide/epub.md#reference)
  - [이미지](guide/epub.md#images)
    - [이미지 크기](guide/epub.md#image-size)
    - [이미지 배치](guide/epub.md#image-position)
    - [이미지 파일명](guide/epub.md#image-file-name)
    - [이미지 색상 모드](guide/epub.md#image-colorspace)
    - [이미지 확장자](guide/epub.md#image-format)
    - [이미지 태그](guide/epub.md#image-tag)
    - [이미지 테두리선 따기 (누끼)](guide/epub.md#image-refine-edge)
    - [이미지 내 글자 크기](guide/epub.md#font-size-in-image)
  - [폰트](guide/epub.md#font)
    - [폰트 크기](guide/epub.md#font-size)
    - [폰트 단위](guide/epub.md#font-unit)
  - [HTML(Spine)](guide/epub.md#html)
    - [HTML 파일 크기](guide/epub.md#html-file-size)
    - [페이지 구성](guide/epub.md#html-layout)
    - [목차](guide/epub.md#html-toc)
    - [주석](guide/epub.md#html-footnote)
      - [주석 기본 구조](guide/epub.md#html-footnote-structure)
      - [주석 기본 HTML 구조](guide/epub.md#html-footnote-html-structure)
      - [주석 제목 HTML 예시](guide/epub.md#html-footnote-title-ex)
      - [주석 설명 HTML 예시](guide/epub.md#html-footnote-body-ex)
  - [EPUB 테스트](guide/epub.md#epub-test)
    - [유효성 검사 - Sigil](guide/epub.md#epub-validation-by-sigil)
    - [파일보기 - 리디북스 뷰어](guide/epub.md#epub-test-by-app)
- [PDF 제작 가이드](guide/pdf.md)
  - [서문](guide/pdf.md#preface)
    - [안내](guide/pdf.md#foreword)
    - [권장사항](guide/pdf.md#recommand)
  - [파일 다운사이징](guide/pdf.md#file-down-sizing)
  - [sRGB 모드 변환](guide/pdf.md#colorspace-convert-to-srgb)
  - [책갈피 삽입](guide/pdf.md#insert-bookmark)
  - [재단선 삭제](guide/pdf.md#crop-cutting-line)

## EPUB 지원

리디북스는 IDPF(Independent Digital Publishing Forum)에서 관리하는 전자책 공개 표준인 EPUB을 지원합니다.

현재 지원 중인 버전은 EPUB 2.0.1이며, EPUB 3는 지원하지 않고 있습니다.

EPUB 3를 지원하지 않고 있지만, HTML5 및 CSS3를 기반으로하며 스펙의 일부를 따르고 있습니다.

EPUB 2 호환용으로 제작된 EPUB 3는 EPUB 2 기반으로 동작합니다.

| 플랫폼     | 지원 여부 |
| ------- | ----- |
| Android | O     |
| iOS     | O     |
| PAPER   | O     |
| Windows | O     |
| macOS   | O     |
| Web     | O     |

## PDF 지원

리디북스는 ISO(International Organization for Standardization)에서 관리하는 국제 표준 문서 형식인 PDF(ISO 32000)를 지원합니다.

현재 지원 중인 버전은 PDF 1.0 ~ 1.7이며, 최신 스펙인 PDF 1.8은 일부 플랫폼에서만 지원하고 있습니다.

| 플랫폼     | 지원 여부 |
| ------- | ----- |
| Android | O     |
| iOS     | O     |
| PAPER   | O     |
| Windows | △     |
| macOS   | △     |
| Web     | X     |
