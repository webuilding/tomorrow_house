# 내일의 집

### 1.GNB

- 로그인을 하지 않은 경우

```html
<div class="button-group">
  <button
    type="button"
    class="gnb-icon-button is-search lg-hidden"
    aria-label="검색창 열기 버튼"
  >
    <i class="ic-search"></i>
  </button>
  <a
    href="/"
    class="gnb-icon-button is-cart"
    aria-label="장바구니 페이지로 이동, 5개의 상품이 장바구니에 담겨있습니다"
  >
    <i class="ic-cart"></i>
  </a>

  <div class="gnb-auth sm-hidden">
    <a href="/" class="">로그인</a>
    <a href="/" class="">회원가입</a>
  </div>
</div>
```

- 로그인을 했을 경우

```html
<div class="button-group">
  <button
    type="button"
    class="gnb-icon-button is-search lg-hidden"
    aria-label="검색창 열기 버튼"
  >
    <i class="ic-search"></i>
  </button>

  <a
    href="/"
    class="gnb-icon-button sm-hidden"
    aria-label="스크랩북 페이지로 이동"
  >
    <i class="ic-bookmark"></i>
  </a>

  <a
    href="/"
    class="gnb-icon-button sm-hidden"
    aria-label="내 소식 페이지로 이동"
  >
    <i class="ic-bell"></i>
  </a>

  <a
    href="/"
    class="gnb-icon-button is-cart"
    aria-label="장바구니 페이지로 이동, 5개의 상품이 장바구니에 담겨있습니다"
  >
    <i class="ic-cart"></i>
    <strong class="badge">5</strong>
  </a>

  <button
    type="button"
    class="gnb-avatar-button sm-hidden"
    aria-label="마이메뉴 열기 버튼"
  >
    <div class="avatar-32">
      <img src="./assets/images/image-user-01.jpg" alt="user-img" />
    </div>
  </button>
</div>
```

### 2.Sidebar

- 로그인을 하지 않은 경우

```html
<div class="sidebar-auth">
  <a class="btn-40 btn-outlined" href="/">로그인</a>
  <a class="btn-40 btn-primary" href="/">회원가입</a>
</div>
```

- 로그인을 한 경우

```html
<div class="sidebar-user">
  <a href="/">
    <div class="avatar-24">
      <img src="./assets/images/image-user-01.jpg" alt="user-img" />
    </div>
    <strong class="username">Nonina</strong>
  </a>
</div>

<div class="sidebar-user-menu">
  <ul class="user-menu-list">
    <li class="user-menu-item"><a href="">마이페이지</a></li>
    <li class="user-menu-item"><a href="">나의 쇼핑</a></li>
    <li class="user-menu-item"><a href="">스크랩북</a></li>
    <li class="user-menu-item"><a href="">알림</a></li>
    <li class="user-menu-item"><a href="">이벤트</a></li>
  </ul>
</div>
```
