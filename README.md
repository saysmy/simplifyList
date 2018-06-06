# Remove duplicate lists

1. Remove spaces and newlines.
2. Remove duplicate lists.

## Install

```
npm i simplify-list -g
```

## Usage

```
simplify-list yourfile.txt
```

#### yourfile.txt

```
baidu/arb/controllers/NoticeController.php
baidu/arb/controllers/NoticeController.php
static_baidu/js/income/incomeDetail.js

static_baidu/js/income/incomeDetail.js
			baidu/arb/views/income/exchangeCashHistory.php
baidu/arb/views/income/exchangeCashHistory.php
```

#### After simplify

```
baidu/arb/controllers/NoticeController.php
static_baidu/js/income/incomeDetail.js
baidu/arb/views/income/exchangeCashHistory.php
```