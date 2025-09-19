OIDC provider
trust and authentication provider

REGION_CODE=us-east-1 CLUSTER_NAME=roboshop-dev ACC_ID=838237641372

eksctl utils associate-iam-oidc-provider \
    --region $REGION_CODE \
    --cluster $CLUSTER_NAME \
    --approve