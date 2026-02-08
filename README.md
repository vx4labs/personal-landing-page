<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=900&size=50&duration=3000&pause=1000&color=FFFFFF&background=00000000&center=true&vCenter=true&width=800&height=100&lines=VX4LABS+%2F+PORTFOLIO" alt="HUD Header" />
  </a>
</div>

<br />

<div align="center">
  <img src="https://img.shields.io/badge/AWS-000000?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Amazon_S3-000000?style=for-the-badge&logo=amazon-s3&logoColor=white" />
  <img src="https://img.shields.io/badge/CloudFront-000000?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Active-000000?style=for-the-badge&logo=github-actions&logoColor=white" />
</div>

<br />
<br />

### ☁️ Architecture Data Flow
```mermaid
graph TD
    User["🌍 Public User"] -->|HTTPS Request| CF["🚀 CloudFront CDN"]
    CF -->|Forward Request| S3["📦 S3 Bucket Origin"]
    S3 -.->|Return Assets| CF
    CF -.->|Deliver Cached Content| User

    style User fill:#f9f9f9,stroke:#333,stroke-width:2px,color:#333
    style CF fill:#232F3E,stroke:#fff,color:#fff
    style S3 fill:#E34F26,stroke:#fff,color:#fff
```

<div align="center">
  <small><i>Solid lines: Initial Request | Dotted lines: Content Delivery Response</i></small>
</div>

<br />
<br />

<div align="center">
  <a href="https://d1qg8ykmv037hc.cloudfront.net">
    <img src="https://img.shields.io/badge/VIEW_LIVE_DEPLOYMENT-LAUNCH_WEBSITE_🚀-000000?style=for-the-badge&logo=safari&logoColor=white&labelColor=1a1a1a" height="45" />
  </a>
</div>

<br />
<br />

<div align="center">
  <h3>🛠 Technical Specifications</h3>
  <br />
  <table>
    <tr>
      <th align="center" width="150">Component</th>
      <th align="center" width="200">AWS Service</th>
      <th align="left">Function Summary</th>
    </tr>
    <tr>
      <td align="center"><b>Storage</b></td>
      <td align="center"><img src="https://img.shields.io/badge/Amazon_S3-222222?style=flat-square&logo=amazon-s3&logoColor=white" /></td>
      <td align="left">Primary storage for static assets. Configured as private origin.</td>
    </tr>
    <tr>
      <td align="center"><b>Delivery</b></td>
      <td align="center"><img src="https://img.shields.io/badge/CloudFront-222222?style=flat-square&logo=amazon-aws&logoColor=white" /></td>
      <td align="left">Global CDN to reduce latency and handle high traffic loads.</td>
    </tr>
    <tr>
      <td align="center"><b>Security</b></td>
      <td align="center"><img src="https://img.shields.io/badge/SSL_&_Policy-222222?style=flat-square&logo=amazon-aws&logoColor=white" /></td>
      <td align="left">Enforced HTTPS and Origin Access Identity (OAI) protection.</td>
    </tr>
  </table>
</div>

<br />
<br />

<div align="center">
  <hr width="60%" />
  <br />
  <small>Documentation & Deployment by <b>VX4Labs</b> | 2026</small>
</div>
