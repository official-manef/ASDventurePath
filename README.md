# Autism Care - Monitoring Platform for Children with Autism Development

## 📋 Project Status
![Status](https://img.shields.io/badge/Status-Development-yellow)
![Version](https://img.shields.io/badge/Version-1.0.0-blue)

## 🎯 Project Goals
AI-powered web platform to assist parents in tracking and improving the development of children with autism.

## 👥 Target Users
- **Primary:** Parents/guardians of children with autism
- **Secondary:** Therapists, caregivers, educators, medical professionals

## ⭐ Key Features
### 1. Personal Dashboard [`STATUS: PLANNED`]
- [ ] Interactive progress charts
- [ ] Progress data visualization
- [ ] Developmental milestone tracking

### 2. Behavior Tracker [`STATUS: IN PROGRESS`]
- [ ] Real-time behavior logging
- [ ] AI-based pattern analysis
- [ ] Automated alert system

### 3. AI Recommendations [`STATUS: PLANNED`]
- [ ] Personalized activity suggestions
- [ ] Transparent machine learning models
- [ ] Explainable AI system

### 4. Community Forum [`STATUS: PLANNED`]
- [ ] Moderated discussion space
- [ ] Private messaging system
- [ ] Thematic discussion groups

### 5. Supporting Features [`STATUS: PLANNED`]
- [ ] Learning library
- [ ] Notification system
- [ ] Multi-language support
- [ ] WCAG accessibility features

## 🛠 Tech Stack
### Frontend
- Next.js (Latest Stable)
- Tailwind CSS
- Redux Toolkit
- React Query
- ShadCN/UI & Radix UI
- next-i18next

### Backend
- Node.js + Express.js
- PostgreSQL + Prisma
- NextAuth.js
- Socket.io

### AI Integration
- PyTorch
- OpenAI API

### DevOps
- GitHub Actions
- Docker + Kubernetes
- Terraform

## 📁 Project Structure
```
./
|-- app/
|   |-- (routes)/
|       |-- dashboard/
|           |-- page.tsx
|           |-- components/
|               |-- ProgressChart.tsx
|               |-- BehaviorTable.tsx
|       |-- login/
|           |-- page.tsx
|       |-- community/
|           |-- page.tsx
|           |-- components/
|               |-- PostList.tsx
|               |-- PostForm.tsx
|-- components/
|   |-- UI/
|       |-- Button.tsx
|       |-- Card.tsx
|   |-- Layout/
|       |-- Header.tsx
|       |-- Footer.tsx
|   |-- Forms/
|       |-- LoginForm.tsx
|       |-- BehaviorLogForm.tsx
|-- hooks/
|   |-- useAuth.ts
|   |-- useFetch.ts
|-- context/
|   |-- AuthContext.tsx
|   |-- ThemeContext.tsx
|-- lib/
|   |-- api/
|       |-- auth.ts
|       |-- user.ts
|       |-- behavior.ts
|   |-- utils/
|       |-- helpers.ts
|       |-- validators.ts
|-- constants/
|   |-- routes.ts
|   |-- apiEndpoints.ts
|-- types/
|   |-- user.d.ts
|   |-- behavior.d.ts
|-- tests/
|   |-- components/
|   |-- pages/
|-- public/
|   |-- images/
|   |-- icons/
|   |-- locales/
|-- styles/
|   |-- globals.css
|   |-- tailwind.css
|-- middleware/
|   |-- authMiddleware.ts
|-- i18n/
|   |-- en/
|   |-- es/
|   |-- fr/

```


## 🎯 Milestones & Progress

### Phase 1: Research & Planning (3 weeks)
- [x] Needs analysis
- [ ] Data privacy framework
- [ ] Detailed roadmap

### Phase 2: Prototype (4 weeks)
- [ ] Interactive prototype
- [ ] Development setup
- [ ] Stakeholder validation

### Phase 3: MVP (8 weeks)
- [ ] Core features
- [ ] Backend API
- [ ] Basic AI integration

### Phase 4-6: Advanced Development (10+ weeks)
- [ ] AI enhancement
- [ ] Testing
- [ ] Deployment
- [ ] Maintenance

## 📊 Success Metrics
| Metric              | Target            | Status       |
|---------------------|-------------------|--------------|
| User Retention      | 60% (6 months)   | 🟡 Pending   |
| AI Feedback         | 85% positive     | 🟡 Pending   |
| Manual Reduction    | 50%              | 🟡 Pending   |
| Uptime              | 99.9%            | 🟡 Pending   |

## 🔒 Security & Compliance
- [ ] GDPR Compliance
- [ ] HIPAA Compliance
- [ ] End-to-end encryption
- [ ] MFA Implementation

## 📝 Documentation
- [Local Setup](docs/setup.md)
- [Contribution Guide](docs/contributing.md)
- [API Docs](docs/api.md)

## 🤝 Team & Contribution
- UI/UX Team: Progress [===>     ] 30%
- Backend Team: Progress [===>     ] 30%
- AI/ML Team: Progress [=>        ] 10%
- DevOps Team: Progress [==>      ] 20%

## 📫 Contact
- Project Manager: [rahmanef63@gmail.com]
- Technical Lead: [rahmanef63@gmail.com]

---

## Catatan pemeliharaan (17 Oktober 2026)

This repository is a fork of [rahmanef63/ASDventurePath](https://github.com/rahmanef63/ASDventurePath). Preserve applicable upstream license terms and notices when changing or redistributing the project.

### Run locally

The repository includes a `package-lock.json` and these npm scripts:

```sh
npm ci
npm run dev
```

Open the local URL printed by Next.js. To run the production server, first build and then start it:

```sh
npm run build
npm start
```

`npm run lint` invokes the configured lint script. These commands are documented from `package.json`; they have not been verified here.

### Current code map and scope

- `app/` contains the Next.js routes, including the home page, `/dashboard`, `/progress`, `/community`, `/reports`, `/resources`, and `/studio`.
- `components/pages/` contains page components for progress, community, reports, resources, and dashboard-related views.
- `sanity/` and the Sanity configuration files provide the project’s content-studio setup.
- The dashboard route currently renders a heading and placeholder comments; dashboard components elsewhere in the repository do not mean that route is fully wired up.
- The README’s listed backend, AI, compliance, and deployment plans are not evidence that those systems are implemented. The repository scripts declare no test command, and no test results are reported here.
