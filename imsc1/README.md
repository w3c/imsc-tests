# IMSC1 Test suite

The IMSC1 Test suite consists of TTML source files located under `./ttml`, and matching exemplar renderings under
`./png`. 

The exemplar renderings are generated using the [imscJS](https://github.com/sandflow/imscJS) library. The root
container is mapped onto a 640x360 gray pixel array as specified in [Section 6.7.1 of IMSC1](https://www.w3.org/TR/ttml-imsc1.0.1/#ittp-aspectRatio). Note that:

- the root container does not fill the pixel array in its entirety unless (i) `ittp:aspectRatio` is not specified, or
(ii) `ittp:aspectRatio` is equal to the aspect ratio of the pixel array

- the value of `tts:extent` on the `tt` element is not used to determine the portion of the pixel array occupied by
the root container, but instead to determine the dimensions of a `px` unit relative to the root container

Each exemplar rendering corresponds to an ISD, with the media time (in seconds) of the ISD encoded in the file name.

The `./tests.json` file lists all tests.


# Bug reports

Please report all bugs at https://github.com/w3c/imsc-tests/issues.


# Ackowledgements

## Institut für Rundfunktechnik (IRT)

The following artifacts under `./ttml` are derived from [tests](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples) created by the [Institut für Rundfunktechnik](https://www.irt.de/en), under this [license](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples/blob/75933dd2c7f378cf6ce06118a74838c20ea905d5/LICENSE).

* br-in-p-001.ttml
* br-in-span-001.ttml
* cellresolution-001.ttml
* content-in-multiple-div-001.ttml
* cumulative-rows-001.ttml
* cumulative-rows-002.ttml
* cumulative-words-001.ttml
* cumulative-words-002.ttml
* displayalign-after-001.ttml
* displayalign-before-001.ttml
* displayalign-center-001.ttml
* fontsize-001.ttml
* font-style-normal-001.ttml
* font-weight-001.ttml
* font-weight-normal-001.ttml
* foreign-namespace-in-header-001.ttml
* foreign-namespace-in-p-001.ttml
* four-active-regions-001.ttml
* idrefs-style-001.ttml
* initial-value-cellresolution-001.ttml
* lineheight-001.ttml
* linepadding-001.ttml
* multirow-align-center-auto-001.ttml
* multirow-align-center-center-001.ttml
* multirow-align-center-end-001.ttml
* multirow-align-center-start-001.ttml
* multirow-align-end-center-001.ttml
* multirow-align-end-start-001.ttml
* multirow-align-start-center-001.ttml
* multirow-align-start-end-001.ttml
* mutiple-regions-sequence-001.ttml
* overflow-hidden-001.ttml
* overflow-visible-001.ttml
* padding-four-values-001.ttml
* padding-one-value-001.ttml
* padding-three-values-001.ttml
* padding-two-values-001.ttml
* space-preserve-001.ttml
* special-character-001.ttml
* styleInheritance-001.ttml
* textalign-center-001.ttml
* textalign-end-001.ttml
* textalign-left-001.ttml
* textalign-right-001.ttml
* textalign-start-001.ttml
* text-decoration-none-001.ttml
* timing-on-span-001.ttml
* timing-on-span-002.ttml
* unicode-bidi-embed-direction-ltr-001.ttml
* unicode-bidi-override-direction-rtl-001.ttml
* wrapoption-nowrap-001.ttml
* wrapoption-wrap-001.ttml
* writing-mode-lr-001.ttml
* writing-mode-lrtb-001.ttml
* writing-mode-rl-001.ttml
* writing-mode-rltb-001.ttml
* writing-mode-tb-001.ttml
* writing-mode-tbrl-001.ttml



## W3C

The following artifacts under `./ttml` are derived from the [TTML](https://github.com/w3c/ttml1/tree/gh-pages/testsuite) and [IMSC](https://github.com/w3c/imsc/tree/master/imsc1/test) implementation reports.

* altText1.ttml
* Animation001.ttml
* Animation002.ttml
* Animation003.ttml
* Animation004.ttml
* Animation007.ttml
* Animation008.ttml
* Animation012.ttml
* Animation013.ttml
* Animation014.ttml
* Animation015.ttml
* Animation016.ttml
* Animation017.ttml
* aspectRatio4.ttml
* aspectRatio4-img.png
* aspectRatio5.ttml
* aspectRatio6.ttml
* aspectRatio6-img.png
* aspectRatio1.ttml
* aspectRatio2.ttml
* aspectRatio3.ttml
* aspectRatio3-img.png
* BackgroundColor001.ttml
* BackgroundColor002.ttml
* BackgroundColor003.ttml
* BackgroundColor004.ttml
* BackgroundColor005.ttml
* BackgroundColor006.ttml
* BackgroundColor007.ttml
* BackgroundColor008.ttml
* BackgroundColor009.ttml
* backgroundColor-region-p-span-001.ttml
* backgroundColor-region-p-span-002.ttml
* backgroundcolor-rgba-001.ttml
* BasicTimeContainment001.ttml
* BasicTimeContainment002.ttml
* BasicTimeContainment003.ttml
* BasicTimeContainment004.ttml
* BasicTiming001.ttml
* BasicTiming002.ttml
* BasicTiming003.ttml
* BasicTiming005.ttml
* BasicTiming006.ttml
* BasicTiming007.ttml
* BasicTiming008.ttml
* BasicTiming010.ttml
* BasicTiming011.ttml
* BasicTiming012.ttml
* BeginDur001.ttml
* BeginEnd001.ttml
* BeginEnd002.ttml
* BeginEnd003.ttml
* Br001.ttml
* Color001.ttml
* Color002.ttml
* Color003.ttml
* Color004.ttml
* Color005.ttml
* Color007.ttml
* Color008.ttml
* Color009.ttml
* Direction001.ttml
* Direction002.ttml
* Direction003.ttml
* Direction004.ttml
* Direction005.ttml
* Direction006.ttml
* Display001.ttml
* Display002.ttml
* Display004.ttml
* DisplayAlign001.ttml
* DisplayAlign002.ttml
* DisplayAlign003.ttml
* Div001.ttml
* Div002.ttml
* Div003.ttml
* DocumentExample120.ttml
* DocumentExample822.ttml
* DocumentExample823.ttml
* DocumentExample824.ttml
* DocumentExample825.ttml
* Extent001.ttml
* Extent002.ttml
* FixedBeginEnd002.ttml
* FontFamily001.ttml
* FontFamily002.ttml
* FontFamily003.ttml
* FontFamily004.ttml
* FontFamily005.ttml
* FontFamily006.ttml
* FontFamily007.ttml
* FontFamily008.ttml
* FontFamily009.ttml
* FontSize001.ttml
* FontSize002.ttml
* FontSize004.ttml
* FontStyle001.ttml
* FontStyle002.ttml
* FontStyle003.ttml
* FontWeight001.ttml
* FontWeight002.ttml
* forcedDisplay1.ttml
* Foreign001.ttml
* LineHeight001.ttml
* LineHeight002.ttml
* LineHeight003.ttml
* LineHeight006.ttml
* linePadding1.ttml
* MediaParTiming001.ttml
* MediaParTiming002.ttml
* MediaParTiming003.ttml
* MediaSeqTiming001.ttml
* MediaSeqTiming002.ttml
* MediaSeqTiming003.ttml
* MediaSeqTiming004.ttml
* MediaSeqTiming005.ttml
* MediaSeqTiming006.ttml
* MediaSeqTiming007.ttml
* multiRowAlign1.ttml
* Opacity001.ttml
* Opacity002.ttml
* Opacity003.ttml
* Opacity004.ttml
* Origin001.ttml
* Origin002.ttml
* Overflow001.ttml
* Overflow002.ttml
* Overflow003.ttml
* Overflow004.ttml
* Overflow005.ttml
* Padding001.ttml
* Padding002.ttml
* Padding003.ttml
* Padding004.ttml
* Padding006.ttml
* Padding007.ttml
* Paragraph001.ttml
* Paragraph002.ttml
* Paragraph003.ttml
* Paragraph004.ttml
* Paragraph005.ttml
* Parameters006.ttml
* progressivelyDecodable1.ttml
* referenceFonts1.ttml
* ShowBackground001.ttml
* ShowBackground002.ttml
* Span001.ttml
* Span002.ttml
* Span003.ttml
* Span004.ttml
* Span005.ttml
* Style001.ttml
* Styling001.ttml
* TextAlign001.ttml
* TextAlign002.ttml
* TextAlign003.ttml
* TextAlign004.ttml
* TextAlign005.ttml
* TextAlign006.ttml
* TextDecoration001.ttml
* TextDecoration002.ttml
* TextDecoration003.ttml
* TextDecoration004.ttml
* TextDecoration005.ttml
* TextDecoration006.ttml
* TextDecoration007.ttml
* TextDecoration008.ttml
* TextDecoration009.ttml
* TextDecoration010.ttml
* TextDecoration011.ttml
* TextDecoration012.ttml
* TextDecoration013.ttml
* TextOutline001.ttml
* TextOutline002.ttml
* TextOutline004.ttml
* Tt001.ttml
* Tt002.ttml
* Tt003.ttml
* UnicodeBidi001.ttml
* UnicodeBidi002.ttml
* UnicodeBidi003.ttml
* UnicodeBidi005.ttml
* Visibility001.ttml
* Visibility002.ttml
* Visibility003.ttml
* WrapOption001.ttml
* WrapOption002.ttml
* WrapOption003.ttml
* WrapOption004.ttml
* WrapOption005.ttml
* WritingMode001.ttml
* WritingMode002.ttml
* WritingMode003.ttml
* WritingMode004.ttml
* WritingMode005.ttml
* WritingMode006.ttml
* WritingMode007.ttml
* WritingMode008.ttml
* WritingMode009.ttml
