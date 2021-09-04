---
title: Getting Started
author: three.balance
date: 2021-09-04 22:46:00 +0900
categories: [Blogging, Tutorials]
tags: [getting started]
pin: true
---

## 전제조건
1. [링크](https://jekyllrb.com/docs/installation/)로 들어가서 요구사항에 맞는 `Ruby`, `RubyGems`, `Jekyll`, `Bundler`를 설치한다.
2. `Ruby`의 버전은 반드시 [RubyGems.prg](https://rubygems.org/gems/jekyll-theme-chirpy)의 테마 요구사항을 충족시켜야한다.

## 설치
테마 설치에는 두가지 방식이 있다.
- ** [Install from RubyGems](#install-from-rubygems) ** - 업데이트 하기 쉽다고 한다.
- ** [Fork on GitHub](#fork-on-github) ** - 업데이트는 어렵지만 개발 상의 편리함이 있어서 웹 개발자들에게 좋아보인다고 한다.

### Install from RubyGems
<b>Notice</b> : 이 부분은 제가 시도해 본 것이 아니라 그냥 번역만 한 것이기 때문에 부디 저를 믿지 마시기 바랍니다.

1. 나만의 Jekyll site 의 `Gemfile`에 아래의 ruby 명령어를 추가한다.
```ruby
gem "jekyll-theme-chirpy"
```

2. 나만의 Jekyll site 의 `_config.yml` 파일에 아래를 yaml 코드를 추가한다.
```yaml
theme: jekyll-theme-chirpy
```

3. 그 다음 실행시킨다.
```console
$ bundle
```

4. 설치된 로컬 테마 경로로 이동한다.
```console
$ cd "$(bundle info --path jekyll-theme-chirpy)"
```

5. 테마 gem에서 중요 파일들을 나만의 Jekyll site 에 복사한다. (자세한 사항은 [링크](https://github.com/cotes2020/chirpy-starter)를 참고


> ⚠️ ** 복사 파일들을 조심하라고 한다. **
>
> 나만의 Jekyll site 가 `jekyll new` 명령어를 통해 만들어졌다면, 나의 Jekyll site 의 root 디렉토리에 `index.markdown`, `about.markdown` 파일이 있을 텐데 이 2개의 파일을 없애거나 링크의 `index.html` 과 `_tabs/about.html` 파일로 각각 덮어씌우기를 권장한다.








