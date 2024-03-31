## part3-chapter2

# 금융 서비스(보안키패드/휴대폰 인증)

<img src="https://github.com/soommmin/part3-chapter2/assets/150005268/dc2c0956-b34e-466e-8158-50711bcc5ffd" width="200" height="400"/>
<img src="https://github.com/soommmin/part3-chapter2/assets/150005268/2a368ef3-fd68-4fd4-9877-1001584b3807" width="200" height="400"/>
<img src="https://github.com/soommmin/part3-chapter2/assets/150005268/4293f0c1-5ede-48b3-aed5-4bdc15026d4a" width="200" height="400"/>


금융 서비스 앱은 GridLayout을 사용하여 앱의 인터페이스를 구성하고, TextInputLayout을 이용하여 사용자가 안전한 비밀번호를 설정할 수 있도록 UI를 디자인합니다.
사용자가 비밀번호를 입력할 때, 정규 표현식을 사용하여 연속된 숫자 등의 보안 취약점을 차단하고, 안전한 비밀번호 설정을 유도합니다.
또한, 사용자의 편의성을 고려하여 SMS 인증 서비스를 구현합니다. 이를 위해 SmsRetriever를 활용하여 사용자가 인증 코드를 수신하면 자동으로 해당 코드를 앱에 입력할 수 있도록 지원합니다. 


## What I Learned
1. GridLayout
   - GridLayout을 사용하면 뷰의 크기와 위치를 유연하게 조절할 수 있습니다.화면 크기가 변경되거나 다양한 디바이스에서 앱이 일관된 방식으로 표시될 수 있도록 설계할 수 있습니다.
2. DataBinding
   - DataBinding은 안드로이드 앱에서 데이터와 UI를 연결하여 간단하고 효율적으로 데이터를 표시하는 데 사용됩니다. 이를 통해 XML 레이아웃에서 바인딩 표현식을 사용하여 UI 요소를 동적으로 업데이트할 수 있습니다. 
3. BindingAdapter
   - BindingAdapter는 DataBinding을 확장하여 사용자 지정 바인딩 표현식을 정의하는 데 사용됩니다. 이를 통해 XML 레이아웃에서 사용자 지정 UI 속성이나 동작을 구현할 수 있습니다. 
4. TextInputLayout
   - TextInputLayout은 안드로이드 디자인 라이브러리에서 제공하는 위젯 중 하나로, EditText를 더욱 유연하고 사용하기 쉽게 만들어주는 역할을 합니다.
5. 정규 표현식
   - 정규 표현식(Regular Expression)은 문자열의 패턴을 정의하고 찾아내는 데 사용되는 형식 언어입니다. 주로 텍스트 처리 작업에서 특정 패턴을 매칭하거나 검색하고 대체하는 데에 쓰입니다.
     정규 표현식은 다양한 문자열 조합을 표현할 수 있습니다. 예를 들어, 특정 문자나 문자 그룹, 숫자 패턴, 공백, 특수 문자 등을 찾거나 대체할 수 있습니다. 이를 통해 주어진 문자열 내에서 원하는 내용을 효율적으로       추출하거나 조작할 수 있습니다.
6. CountDownTimer
   - 일정 시간 동안 카운트다운을 수행하는 기능을 제공합니다. 특정 시간이 경과할 때마다 일정한 간격으로 콜백 메서드를 호출하여 사용자가 원하는 작업을 수행할 수 있도록 합니다.
7. SmsRetriever
   - SmsRetriever는 안드로이드 플랫폼에서 제공하는 기능 중 하나로, 앱이 SMS 메시지를 자동으로 수신하여 처리할 수 있도록 도와주는 서비스입니다.
   - 앱은 SMS 메시지를 자동으로 수신하여 특정 패턴의 인증 코드나 메시지를 추출할 수 있습니다. 이를 통해 사용자는 앱에 입력하는 번거로움 없이 SMS 메시지에 포함된 인증 코드를 자동으로 인식하여 처리할 수 있습니다.





