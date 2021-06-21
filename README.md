# deploy-test


```
echo "# deploy-test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/ynawhocodes/deploy-test.git
git push -u origin master
```

0. 폴더 생성 후 VSCode로 폴더 오픈

1. 가상 환경 생성
`python -m venv [가상 환경 이름]`
```
python -m venv myvenv
```

2. 가상 환경 실행 `source [가상 환경 이름]/Scripts/activate`
for Window
```
source myvenv/Scripts/activate
```

3. django 설치
```
pip install django
```

5. 프로젝트 생성 `django-admin startproject [프로젝트 이름]`
```
django-admin startproject myproject
```
