## 챕터1 MatchGame

게임설명 : 격자 안에 위치한 8쌍의 동물을 클릭해서 짝을 맞추면 해당 동물이 사라지는 게임.

### MainWindow.xaml.cs

Timer_Tick(object sender, EventArgs e) : 타이머 기능 구현

SetUpGame() : 동물 배치, 타이머 초기화, 맞춘 개수 초기화

TextBlock_MouseDown(object sender, MouseButtonEventArgs e) : 동물 클릭 시 기능 구현

TimeTextBlock_MouseDown(object sender, MouseButtonEventArgs e) : 타이머 클릭 시 재시작




