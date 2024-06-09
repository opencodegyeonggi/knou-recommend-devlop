# Code

## Index

- [Code](#code)
  - [Index](#index)
  - [JavaScript(Node)](#javascriptnode)
  - [Java](#java)
  - [DataBase](#database)
  - [SSH, FTP](#ssh-ftp)
  - [VCS](#vcs)
  - [More](#more)

## JavaScript(Node)

> [!NOTE]
> Node의 경우 기본적으로 텍스트 기반이다 보니 정말 많은 툴이 존재하여, 작성자기준에서 많이 들어본 항목들만 나열하도록 하겠습니다. (툴이 너무많아서 ㅎㅎ;;)
>
> 추가하고 싶은 항목들은 PR로 추가해주시기 바랍니다.

- [`NotePad++`](https://notepad-plus-plus.org/)
  - 무료긴 한데..
  - 기본적으로 텍스트 에디터라 개발이 가능합니다..
- [`Visual Studio Code`](https://code.visualstudio.com/)
  - 무료
  - 필자가 자주 사용합니다.
- [`Cursor`](https://www.cursor.com/)
  - 무료
  - `Visual Studio Code`에서 AI를 통한 코드작성 기능이 같이 합쳐진 것으로 알고있습니다.
- [`WebStorm`](https://www.jetbrains.com/webstorm/promo/?source=google&medium=cpc&campaign=APAC_en_KR_WebStorm_Branded&term=webstorm&content=523833970958&gad_source=1&gclid=Cj0KCQjwpZWzBhC0ARIsACvjWROD5kORT6Gux2up8hypQ6Wb-J8YWc69_7BS6IMLcvIP9USUG6yAwQMaAmiPEALw_wcB)
  - 유료
  - JetBrains에서 만든 툴로, 학생인증시 무료 사용가능합니다.
  - 호불호가 많이 갈린다 생각합니다.

## Java

> [!NOTE]
> 자바의 경우 유명한 툴로는, `Intellij`, `Eclipse`, `Visual Studeio Code(VSCode)`, `NetBeans(전설로 들어보기만 함)`정도가 존재하나, 다른 다양한 툴틀이 더 존재합니다.
> 그 중 최근에 자주 사용되는 툴은 `Intellij`, `Eclipse`정도만 사용이 되다보니 두개에 대해서만 간단히 설명합니다.

> [!TIP]
>
> `Visual Studio Code`로의 Java 개발이 가능하다는걸 아는 시점에서, 이 글을 읽지 않으셔도 되는 분이기 때문이죠.. 🤣🤣
> 입문자에게 Java IDE로 VSCode를 권장하고 싶진 않아서 기록하지 않았습니다.

- `Eclipse`
  - 다양한 플러그인이 존재하여, 자유롭게 설치와 커스터마이징이 가능.
  - 완전 무료
  - 전자정부 프레임워크 툴이 `Eclipse`를 기반으로 제작되어져 있어, 전자정부프레임워크로 개발하는 회사를 목표하는 경우 도움이 될 수 있음.
  - 여러개의 프로젝트가 한개의 디렉토리 안에 존재하는 경우 해당 프로젝트를 모두 로드하는게 가능
    - 여러개의 프로젝트를 동시에 로드하는 경우 느려질 수 있다. 이점 주의
- `Intellij`
  - JetBrains에서 제작한 IDE도구로, Java언어를 개발함에 있어서 Eclipse의 인기를 뻈어오고 있는 툴.
  - 무료인 커뮤니티 버젼과, 유료인 Ultimate버전이 존재함.
    - 무료로도 충분히 스프링 기반의 개발이 가능하나, Ultimate에 편의성을 많이 제공해주고 있어 한층 개발이 수월함.
    - 학생인 경우, 학생 메일을 활용하는 경우 JetBrains의 모든 툴을 1년간 무료로 사용 가능한 라이센스를 제공함.
  - 한개의 프로젝트만 로드가 가능하다.

## DataBase

> [!NOTE]
> DataBase의 경우에도 터미널로만 DB의 조회는 가능하나, 불편한 부분이 너무 많기에 Tool을 이용합니다.  
> DB Tool에도 여러 종류가 있으며, 취향에 맞춰, 상황에 맞춰 다양한 종류를 사용해 보면 됩니다.

> [!CAUTION]
> 전체적으로 모든 DB와 연결 가능한 툴들에는 없는 기능들이 전용 툴에는 존재하는 경우가 있습니다.  
> 그런 경우에는 해당 툴들을 사용해야 하는 경우가 있을 수 있습니다.

- Oracle 전용
  - [SQL Developer](https://www.oracle.com/kr/database/sqldeveloper/)
- MySQL, MariaDB 전용
  - [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)
- MS-SQL
  - [SQL Server](https://www.microsoft.com/ko-kr/sql-server/sql-server-downloads)
- 전체 DB 연결 가능 Tool
  - [DBeaver](https://dbeaver.io/download/)
  - [DataGrip](https://www.jetbrains.com/ko-kr/datagrip/)
    - 유료, 학생인증시 사용가능
  - 그 외.. (사용률이 높지 않아서.. 별다른 기록을 하지 않음)

## SSH, FTP

> [!NOTE]
> 타 PC(서버)와 SSH연결, FTP를 통한 파일전송을 하기 위해 자주 사용하며, JavaScript툴처럼 많은 종류가 존재하여, 필자가 사용해봤던 툴들만 기록하도록 하겠습니다.

- [Putty](https://www.putty.org/)
  - 무료
  - Windows, Mac 둘다 사용은 가능
  - FTP는 안되던것으로 기억
- [WinScp](https://winscp.net/eng/download.php)
  - 무료 오픈소스
  - Windows용
  - 파일 전송 및 SSH 둘다 가능
- [MobaXterm](https://mobaxterm.mobatek.net/)
  - 유료
  - 파일전송 및 SSH 둘다 가능
- [FileZilla](https://filezilla-project.org/)
  - 무료
  - Windows, Mac 둘다 사용 가능
  - FTP를 통한 파일전송 및 AWS같은 클라우드도 가능
- [Visual Studio Code](https://code.visualstudio.com/)
  - 무료
  - Windows, Mac 둘다 사용 가능
  - SSH, FTP 둘다 사용 가능
  - 뉴비 권장
- `터미널`
  - OS의 터미널을 통한 커맨드
  - 현재 필자가 자주 사용하는 방법입니다.
    - 튜닝의 끝은 순정이라고 들어서..
  - SSH, FTP둘다 사용 가능

## VCS

> [!NOTE]
> Version Control을 할 수 있는 클라이언트 툴도 많은 종류가 있는걸 알고 계셨나요? 툴은 취향입니다~

- `터미널 커맨드`
  - Windows는 `Git Bash`, `PowerShell`등등
  - Mac, Linux는 `bash`, `iterm` 등등의 터미널
  - 초기에는 터미널을 권장합니다.
    - 자신이 어떤 커맨드를 치고있는지를 알아야 추후 툴에서 사용시 편리했던 것 같습니다.
    - 결국 GUI툴들도 터미널을 대신 입력해 주는것 뿐입니다.
- [Source Tree](https://www.sourcetreeapp.com/)
  - 무료
  - Mac, Windows
  - 가장 직관적이고 쉬운 UI
- [Git Kraken](https://www.gitkraken.com/)
  - 유료
  - Mac, Windows
  - 학생서비스 같은것은 없음.
- [GitHub Desktop](https://desktop.github.com/)
  - 무료
  - Mac, Windows
- [Visual Studio Code](https://code.visualstudio.com/)
  - 무료
  - Mac, Windows
  - 무난합니다.

## More

> [!IMPORTANT]
> 추가가 필요해 보이는 항목, 있으면 Issue로 기록 남겨주시면 적어놓도록 하겠습니다.
