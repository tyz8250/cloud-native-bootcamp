## Project Status

AWS Cloud Native Bootcampの学習記録です。

### Completed
- S3 Static Website Hosting
- CloudFront Distribution
- Cache Hit / Miss Verification
- Architecture Diagrams

### Security
- S3 Public Access Block: Enabled
- Public Read Bucket Policy: Removed
- CloudFront OAC: Not yet configured

現在、S3バケットを非公開に戻しています。
そのため、CloudFront経由でのサイト表示は
正常に動作しない場合があります。

### Next
- CloudFront + OAC
- Cache Invalidation
- Terraform

AWS公式Cloud Native Bootcampを参考に、S3による静的Webサイト公開、CloudFrontによるキャッシュ配信、アクセス制御を実践した学習プロジェクトです。構成図と検証結果、セキュリティ上の設計判断を記録しています。