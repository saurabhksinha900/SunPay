# SunPay

# SunPay: The UPI of Clean Energy — Powered by AI & Agentforce
# Inspiration
Across the globe, billions of kilowatt-hours of solar energy go unutilized every year — especially from rooftops in sunny regions like Africa, Southeast Asia, Latin America, and Southern Europe. Yet, individuals and businesses lack access to local green energy, while grids struggle with sustainability goals.

Inspired by the success of India's UPI (Unified Payments Interface) and the vision to decentralize clean energy (as highlighted by Infosys co-founder Nandan Nilekani), SunPay was born. Our goal: turn every rooftop into a micro-entrepreneur by enabling anyone to sell surplus solar power instantly, securely, and intelligently — using AI.

# What it does
SunPay is a decentralized, AI-powered marketplace built on Salesforce Agentforce. It lets users buy and sell clean energy locally and instantly, powered by a network of autonomous agents.

# Key Capabilities
Peer-to-Peer Solar Trading: Connect buyers and sellers of solar energy via an AI-powered matching engine.
Autonomous Negotiation: Agents negotiate energy rates dynamically based on demand, location, and grid conditions.
Instant Settlements: UPI-like transactions for energy (e.g., $/kWh) using a secure digital ledger.
Lead & Contact Capture: All interactions auto-convert to Salesforce leads for follow-up or onboarding.
Carbon Impact Tracking: View your CO₂ savings with every trade and align with ESG goals.
Accessible on Any Device: Our solution includes a responsive web portal and mobile apps (iOS and Android), making it easy for users to trade and track energy anytime, anywhere.
Every 1 kWh traded saves 0.8 kg of CO₂. SunPay makes climate action profitable, simple, and scalable.

# How we built it
SunPay was created in under 3 days using Salesforce Agentforce, without writing traditional code.

# Components
Salesforce Custom Objects:
Seller, Buyer, EnergyListing, Transaction, CarbonCredit
AI Agents Created Using Prompts:
Market-Maker Agent: Matches sellers to buyers
Buyer Finder Agent: Recommends local clean energy options
Negotiation Agent: Offers 10–15% flexible pricing with seller/buyer context
Payment Validator Agent: Checks payment status and fraud flags
Lead Generator Agent: Captures contact info and auto-creates Salesforce leads
Forecasting Agent: Predicts kWh availability using weather patterns
Alert Agent: Notifies users of price drops and energy availability
Data Setup
Generated 1,000+ realistic records for buyers and sellers using synthetic datasets with:
Location, Surplus/Demand, $/kWh pricing, and contact info
Loaded into Salesforce via CSV and converted to Agentforce-compatible knowledge files (HTML/text)
Zero-Code Agent Creation
Used natural language prompts to create each agent — defining role, purpose, data source, and interaction flow. Even users new to Salesforce were able to build this using the intuitive Agentforce UI and documentation.

# Challenges we ran into
Agent Looping: Agents occasionally repeated steps or misunderstood the knowledge base without contextual tuning.
Data Limitations: Agentforce Data Library supports text/HTML, so CSVs had to be reformatted into readable files.
Agent Complexity: Multi-task agents were unstable — we had to break them into modular agents with atomic goals.
Global Scaling Logic: Factoring local currency, solar radiation data, and energy regulations required prompt optimization.
Accomplishments that we're proud of
Built a fully working peer-to-peer solar energy platform without any code.
Designed a globally adaptable framework — usable in India, Brazil, Kenya, Vietnam, or California.
Created 6+ AI agents that work collaboratively to simulate a real-world green energy market.
Quantified carbon savings for each energy trade — enabling measurable climate impact.
Proved that anyone, regardless of technical skill, can create AI-powered climate solutions with Agentforce.
# What we learned
GenAI democratizes innovation — Agentforce let us turn ideas into solutions fast, without developers.
Clean energy needs localized intelligence — agents adapted pricing and suggestions based on geography and timing.
Prompt engineering is user experience — how you instruct the agent determines the power of the AI.
Sustainability doesn't require complexity — simple modular agents can create transformative impact.
# What's next for SunPay
Global Expansion: Launch pilots in Kenya, India, and Latin America with local grid partners and NGOs.
Smart Wallet Integration: Add digital wallets and UPI-like APIs for seamless settlements.
Carbon Credit Marketplace: Let households mint carbon tokens for every kWh traded and sell to corporates.
SunPay Mobile App: Expand our mobile presence to allow energy trading and carbon tracking from any device.
Open APIs for Governments and Utilities: Help DISCOMs, municipalities, and ESG boards integrate with SunPay.
Educational Mode: Help schools, farmers, and local cooperatives use AI agents to participate in sustainable trade.
UN SDG Alignment
SDG Goal	Alignment
Goal 7: Affordable and Clean Energy	Peer-to-peer clean energy access for all
Goal 13: Climate Action	0.8 kg CO₂ avoided per kWh traded
Goal 9: Industry, Innovation & Infrastructure	Digital infrastructure for decentralized energy
Goal 11: Sustainable Cities	Local energy trade reduces urban grid pressure
Goal 17: Partnerships for the Goals	Open APIs to integrate with government and global organizations
# Final Thought
SunPay isn’t just a hackathon project — it’s a blueprint for climate entrepreneurship powered by AI for Good. And with Salesforce Agentforce, the barrier between idea and execution is lower than ever.

# “Why pay the grid, when you can pay your neighbor — and save the planet?”

# Created by the SunPay Team using Salesforce Agentforce — no code, just clean energy innovation.
