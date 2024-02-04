# Security Best Practises

1. Require human users(workforce identities) to use federation with an identity provider to access AWS using temporary credentials
2. Always Require workloads to use temporary credentials with IAM roles to access AWS
3. Require multi-factor authentication (MFA)
4. Update access keys when needed for use cases that require long-term credentials
5. Apply least-privilege permissions
6. Get started with AWS managed policies and move toward least-privilege custom permissions
7. Use IAM Access Analyzer to generate least-privilege policies based on access activity
8. Regularly review and remove unused users, roles, permissions, policies, and credentials
9. Use conditions in IAM policies to further restrict access
10. Verify public and cross-account access to resources with IAM Access Analyzer
11. Use IAM Access Analyzer to validate your IAM policies to ensure secure and functional permissions
12. As you grow start Establishing permissions guardrails across multiple accounts
13. Use permissions boundaries to delegate permissions management within an account

# Root user best practices
1. Do not connect you Account with Root user unless its really really nessesary
2. Secure your root user credentials to prevent unauthorized use
3. Use a strong root user password to help protect access
4. Secure your root user sign-in with multi-factor authentication (MFA)
5. Don't create access keys for the root user
6. Use multi-person approval for root user sign-in wherever possible
7. Use a group email address for root user credentials
8. Restrict access to account recovery mechanisms
9. Secure your Organizations account root user credentials
10. Monitor access and usage

https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html
https://docs.aws.amazon.com/IAM/latest/UserGuide/root-user-best-practices.html



