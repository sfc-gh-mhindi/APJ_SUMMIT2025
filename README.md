# APJ Summit 2025 - End-to-End Data Pipeline Demo

Welcome to the APJ Summit 2025 repository! This contains comprehensive documentation for a multi-squad demonstration of a modern data engineering pipeline using Snowflake's Medallion Architecture.

## 🎯 Overview

This summit showcases an end-to-end data pipeline journey from raw data ingestion to AI-powered insights, demonstrating collaboration between four specialized squads:

- **🔄 DI Squad** - Data Ingestion (Bronze Layer)
- **📦 DM Squad** - Data Migration (Bronze Layer) 
- **⚡ DT Squad** - Data Transformation (Silver Layer)
- **🤖 AIML Squad** - AI/ML Intelligence (Gold Layer)

## 📋 Documentation Structure

### 📖 [`Documentation/APJ_SUMMIT_PLAN.md`](./Documentation/APJ_SUMMIT_PLAN.md)
**Complete Summit Planning Document**
- Detailed architecture overview and medallion layer mapping
- Comprehensive squad responsibilities and deliverables
- Technical specifications for databases and schemas
- Demo vs Hands-On Lab breakdown for each squad
- Timeline, setup requirements, and success criteria

### 🔍 [`Documentation/APJ_SUMMIT_QUICK_REFERENCE.md`](./Documentation/APJ_SUMMIT_QUICK_REFERENCE.md)  
**Inter-Squad Coordination Guide**
- At-a-glance architecture summary tables
- Schema mapping for CAS2 and Sandbox environments
- Critical pre-summit actions and dependencies
- Handoff criteria between squads
- Emergency backup plans and troubleshooting

## 🏗️ Architecture

### Medallion Layer Flow
```
Azure SQL → Bronze (DI/DM) → Silver (DT) → Gold (AIML) → Business Insights
```

### Data Assets
- **Customers**: 1M rows (Azure SQL Box A)
- **Accounts**: 1M rows (Azure SQL Box A)  
- **Transactions**: 50M rows (Azure SQL Box B)

### Environment Strategy
- **CAS2**: Live demo environment with pre-loaded data
- **Sandboxes**: Hands-on lab environments for participants

## 🚀 Getting Started

### For Squad Leaders
1. Review your squad's section in the main planning document
2. Check the quick reference for dependencies and handoff criteria
3. Verify your environment setup requirements
4. Coordinate with adjacent squads for smooth transitions

### For Participants
1. Ensure access to your sandbox environment
2. Complete any pre-summit requirements (especially DM Squad data share)
3. Review the overall data flow to understand your part in the story

## 📊 Success Metrics

- **Technical**: All pipeline stages execute successfully with zero data loss
- **Educational**: 90%+ attendees understand medallion architecture  
- **Business**: Clear demonstration of ROI and competitive advantages

## 🎬 Summit Flow

| Squad | Focus | Mode | Key Message |
|-------|-------|------|-------------|
| **DI** | Data Ingestion | Hands-On Lab | "Raw data lands in Bronze layer" |
| **DM** | Data Migration | Demo + Data Share | "Large-scale migration to Bronze" |
| **DT** | Transformation | Demo + Hands-On Lab | "Business logic creates Silver layer" |
| **AIML** | Intelligence | Demo + Hands-On Lab | "Intelligence creates Gold layer insights" |

## 🔗 Quick Links

- [Complete Planning Document](./Documentation/APJ_SUMMIT_PLAN.md)
- [Quick Reference Guide](./Documentation/APJ_SUMMIT_QUICK_REFERENCE.md)

## 📞 Support

For questions or issues with the summit planning, please reach out to the organizing committee.

---

**Ready to showcase the future of data engineering!** 🚀

*This repository supports the APJ Summit 2025 demonstration of modern data pipeline architecture using Snowflake's native capabilities and AI-powered development tools.*
