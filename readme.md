# Feishu Application SDK Wrapper

## What is this

This is an SDK wrapper based on Feishu's API. It is designed to help developers focus on specific functionalities without worrying about the preliminary handling of various tokens.

## Installation

```
npm i useFeishu 
```

## Usage

```
import UseFeishu from 'usefeishu';

const useFeishu = new UseFeishu(AppID, AppSecret);

const token = await useFeishu.getTenantAccessToken();

```


## Getting tenant_access_token

getTenantAccessToken

## Getting app_access_token

getAppAccessToken

## Sending Messages

sendMessage

## Sending Private Messages in Group Chats - Only Visible to the Recipient

sendPrivateMessage

## Uploading Images

uploadImg