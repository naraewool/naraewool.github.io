# \#1 Go 설치

## Hugo 설치하기

다음은 Hugo를 이용할 수 있는 go 프로그램을 Windows 작업 환경에 설치하는 방법을 소개한다:

{% embed url="https://golang.org/dl/" %}



{% hint style="warning" %}
Go의 설치 파일은 C:\Go에 설치된다. 원하는 곳에 설치 가능하지만 환경 변수 설정이 필요하다. 
{% endhint %}

Once you're strong enough, save the world:

```
// Ain't no code for that yet, sorry
echo 'You got to trust me on this, I saved the world'
```

## Hugo 경로 변경하기

작

{% embed url="https://github.com/golang/go/wiki/SettingGOPATH" %}

작업물이 저장될 위치는 선택 가능하다. 

1. 원하는 위치에 폴더 생성
2. 시작\(Start\) 버튼에서 오른쪽 버튼 눌 **제어판\(Control Panel\)** 선택 &gt; **시스템과 보안 \(System and Security**\) &gt; **시스템**  선 \(제어판\시스템 및 보안\시스템\)
3. 왼쪽의 메뉴에서 **고급 시스템 설정\(Advanced systems\)** 선택
4. **환경 변수\( Environment Variables\)** 버튼 클릭
5. User에 대한 **환경 변수\(User variables\)** 항목에  **새로 만들기\(New\)** 클릭
6. **변수 이름**란에 _GOPATH_ 입력
7. **변수 값**란에 1번 단계에서 생성한 폴더의 경로 입력
8. **확인** 클릭

{% hint style="info" %}
WIndows 10의 경우 



There is a faster way to edit `Environment Variables` via search:

* Left click on "Search" and type `env` or `environment`.
* Select "Edit environment variables for your account".
* ... and follow steps above.

### Windows 10 \(cli version\)

* Open a command prompt \(windows-key + r then type "cmd"\) or a powershell window \(windows-key + i\)
* Type `setx GOPATH %USERPROFILE%\go` \(this will set the `GOPATH` to your `[home folder]\go` e.g. `C:\Users\yourusername\go`
* Close the command or powershell window \(the environment variable is only available for new command or powershell windows, not for the current window\).
{% endhint %}



C:\Users\user\Downloads\img \(추후 추가하기\)



