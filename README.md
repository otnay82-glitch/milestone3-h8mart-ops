# \# H8Mart Quick-Commerce Operations

#

# \## 1. Project Overview

#

# H8Mart Quick-Commerce Operations is an automation project developed as part of the Hacktiv8 Applied AI Engineer Milestone 3.

#

# The project uses n8n workflows to support merchant operations, stock synchronization, order processing, AI-assisted merchant support, compensation and refund handling, and operational reliability monitoring.

#

# \## 2. Business Objectives

#

# \- Automate merchant stock synchronization.

# \- Process incoming customer orders.

# \- Provide daily operational summaries.

# \- Enable merchants to access operational data through AI assistance.

# \- Handle delivery compensation and order refunds.

# \- Monitor workflow execution and operational failures.

#

# \## 3. System Architecture

#

# The solution integrates:

#

# \- n8n for workflow orchestration.

# \- PostgreSQL for operational data storage.

# \- Mock API for simulated business services.

# \- OpenAI for AI-assisted merchant support.

# \- Telegram for operational notifications and approvals.

# \- Uptime Kuma for service monitoring.

#

# \*Detailed architecture documentation: `docs/architecture.md`.\*

#

# \## 4. Workflow Documentation

#

# | Workflow | Description | Status |

# |---|---|---|

# | WF1-A | Stock Synchronization | In Progress |

# | WF1-B | Order Intake | In Progress |

# | WF1-C | Daily Operational Digest | Pending |

# | WF2 | Merchant Data Tools (MCP) | Pending |

# | WF3 | AI Merchant Assistant | Pending |

# | WF4 | Compensation and Refund | Pending |

# | WF5 | Reliability and Monitoring | Pending |

#

# Workflow statuses will be updated based on actual implementation and test evidence.

#

# \## 5. Repository Structure

#

# ```text

# milestone3-h8mart-ops/

# â”œâ”€â”€ README.md

# â”œâ”€â”€ workflows/

# â”œâ”€â”€ docs/

# â””â”€â”€ evidence/

# &#x20;   â”œâ”€â”€ WF1/

# &#x20;   â”œâ”€â”€ WF2/

# &#x20;   â”œâ”€â”€ WF3/

# &#x20;   â”œâ”€â”€ WF4/

# &#x20;   â””â”€â”€ WF5/

# ```

#

# \## 6. Technology Stack

#

# \- n8n

# \- PostgreSQL

# \- OpenAI API

# \- Telegram Bot API

# \- Uptime Kuma

# \- Docker

# \- AWS EC2

#

# \## 7. Configuration and Security

#

# Credentials and sensitive configuration values are managed outside the Git repository.

#

# Do not commit API keys, access tokens, passwords, private keys, or production environment files.

#

# \## 8. Testing and Validation

#

# Workflow execution results, test scenarios, and validation evidence will be documented under the corresponding `evidence/` directories.

#

# \## 9. Deployment

#

# Deployment and configuration instructions will be documented in the project documentation.

#

# \## 10. Project Status

#

# This repository contains the implementation, documentation, and evidence for the H8Mart Quick-Commerce Operations Milestone 3 project.

#

# Final completion status will be based on verified workflow execution and the project assessment requirements.
