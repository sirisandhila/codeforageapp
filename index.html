import React, { useState, useEffect, useRef, useMemo } from "react";
import {
  Terminal,
  ChevronRight,
  ChevronDown,
  Code2,
  Braces,
  Cpu,
  Layers,
  Trophy,
  Users,
  CheckCircle2,
  Star,
  ArrowUpRight,
  Menu,
  X,
  Smartphone,
  Database,
  Brain,
  MessageSquare,
  Flame,
  Clock,
  BookOpen,
  Calendar,
  TrendingUp,
} from "lucide-react";
import {
  ResponsiveContainer,
  AreaChart,
  Area,
  XAxis,
  YAxis,
  Tooltip,
  CartesianGrid,
} from "recharts";

/* ---------------------------------------------------------------
   DESIGN TOKENS
   ink    #12151C  -- near-black ink, dark sections / text
   paper  #F6F3EC  -- warm paper, light sections
   green  #2FBE7F  -- terminal-cursor signal green, primary accent
   amber  #E8A23D  -- warm secondary accent, highlights
   slate  #5B6472  -- muted supporting text
   line   rgba(18,21,28,0.12) -- hairline dividers
   Display: Space Grotesk | Mono/utility: JetBrains Mono | Body: Inter
------------------------------------------------------------------*/

const T = {
  ink: "#050810",
  navy: "#0A1128",
  navyDeep: "#060A1A",
  paper: "#EAF0FF",
  green: "#2FE0A8",
  amber: "#E8A23D",
  slate: "#93A0C2",
  line: "rgba(234,240,255,0.12)",
  lineOnDark: "rgba(234,240,255,0.14)",
  glass: "rgba(20,28,58,0.45)",
  glassBorder: "rgba(234,240,255,0.14)",
};

const FontLoader = () => (
  <style>{`
    @import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@500;600;700&family=JetBrains+Mono:wght@400;500;600&family=Inter:wght@400;500;600;700&display=swap');

    .cf-root {
      font-family: 'Inter', sans-serif;
      color: ${T.paper};
      background:
        radial-gradient(1100px 600px at 15% -10%, rgba(47,224,168,0.10), transparent 60%),
        radial-gradient(900px 500px at 100% 0%, rgba(60,90,200,0.18), transparent 55%),
        linear-gradient(180deg, ${T.ink} 0%, ${T.navy} 45%, ${T.navyDeep} 100%);
      background-attachment: fixed;
      min-height: 100vh;
    }
    .cf-display { font-family: 'Space Grotesk', sans-serif; }
    .cf-mono { font-family: 'JetBrains Mono', monospace; }

    .cf-glass {
      background: ${T.glass};
      -webkit-backdrop-filter: blur(16px) saturate(140%);
      backdrop-filter: blur(16px) saturate(140%);
      border: 1px solid ${T.glassBorder};
    }
    .cf-glass-strong {
      background: rgba(10,17,40,0.65);
      -webkit-backdrop-filter: blur(22px) saturate(150%);
      backdrop-filter: blur(22px) saturate(150%);
      border: 1px solid ${T.glassBorder};
    }

    @keyframes cf-blink { 0%, 49% { opacity: 1; } 50%, 100% { opacity: 0; } }
    .cf-cursor { animation: cf-blink 1s step-start infinite; }

    @keyframes cf-rise { from { opacity: 0; transform: translateY(14px); } to { opacity: 1; transform: translateY(0); } }
    .cf-rise { animation: cf-rise 0.5s ease-out both; }

    .cf-btn-primary { background: ${T.green}; color: ${T.ink}; transition: transform .15s ease, box-shadow .15s ease; }
    .cf-btn-primary:hover { transform: translateY(-1px); box-shadow: 0 12px 24px -10px rgba(47,224,168,0.45); }

    .cf-btn-ghost {
      border: 1px solid ${T.glassBorder};
      color: ${T.paper};
      background: rgba(234,240,255,0.04);
      -webkit-backdrop-filter: blur(10px);
      backdrop-filter: blur(10px);
      transition: border-color .15s ease, background .15s ease;
    }
    .cf-btn-ghost:hover { background: rgba(234,240,255,0.09); border-color: rgba(234,240,255,0.3); }

    .cf-card {
      border: 1px solid ${T.glassBorder};
      background: ${T.glass};
      -webkit-backdrop-filter: blur(16px) saturate(140%);
      backdrop-filter: blur(16px) saturate(140%);
      transition: transform .18s ease, box-shadow .18s ease, border-color .18s ease;
    }
    .cf-card:hover { transform: translateY(-4px); box-shadow: 0 20px 40px -20px rgba(0,0,0,0.5); border-color: rgba(234,240,255,0.3); }

    .cf-focus:focus-visible { outline: 2px solid ${T.green}; outline-offset: 2px; }

    .cf-tab { transition: color .15s ease, border-color .15s ease; }

    @media (prefers-reduced-motion: reduce) {
      .cf-cursor, .cf-rise { animation: none !important; }
    }
  `}</style>
);

/* ================================================================
   TERMINAL HERO SIGNATURE
================================================================= */

const TERMINAL_LINES = [
  { cmd: "learn --track dsa", out: "arrays, trees, graphs -> mastered" },
  { cmd: "build --project 3", out: "shipped: full-stack e-commerce app" },
  { cmd: "mock-interview --company faang", out: "feedback: strong, ready to apply" },
  { cmd: "apply --role sde-1", out: "status: offer received ✓" },
];

function TerminalHero() {
  const [lineIndex, setLineIndex] = useState(0);
  const [charIndex, setCharIndex] = useState(0);
  const [showOut, setShowOut] = useState([false, false, false, false]);

  useEffect(() => {
    if (lineIndex >= TERMINAL_LINES.length) return;
    const current = TERMINAL_LINES[lineIndex].cmd;
    if (charIndex < current.length) {
      const t = setTimeout(() => setCharIndex((c) => c + 1), 32);
      return () => clearTimeout(t);
    } else {
      const t = setTimeout(() => {
        setShowOut((s) => {
          const next = [...s];
          next[lineIndex] = true;
          return next;
        });
        setTimeout(() => {
          setLineIndex((l) => l + 1);
          setCharIndex(0);
        }, 450);
      }, 220);
      return () => clearTimeout(t);
    }
  }, [charIndex, lineIndex]);

  return (
    <div
      className="rounded-xl overflow-hidden w-full max-w-xl cf-rise"
      style={{ background: T.ink, boxShadow: "0 30px 60px -30px rgba(18,21,28,0.55)" }}
    >
      <div className="flex items-center gap-2 px-4 py-3" style={{ borderBottom: `1px solid ${T.lineOnDark}` }}>
        <span className="w-3 h-3 rounded-full" style={{ background: "#E8635B" }} />
        <span className="w-3 h-3 rounded-full" style={{ background: T.amber }} />
        <span className="w-3 h-3 rounded-full" style={{ background: T.green }} />
        <span className="cf-mono text-xs ml-2" style={{ color: "rgba(246,243,236,0.5)" }}>career.sh</span>
      </div>
      <div className="p-5 cf-mono text-[13px] sm:text-sm leading-relaxed min-h-[220px]">
        {TERMINAL_LINES.map((l, i) => {
          if (i > lineIndex) return null;
          const text = i === lineIndex ? l.cmd.slice(0, charIndex) : l.cmd;
          const isTypingThis = i === lineIndex && charIndex < l.cmd.length;
          return (
            <div key={i} className="mb-2">
              <span style={{ color: T.green }}>$</span>{" "}
              <span style={{ color: T.paper }}>{text}</span>
              {isTypingThis && <span className="cf-cursor" style={{ color: T.paper }}>▍</span>}
              {showOut[i] && (
                <div className="pl-4" style={{ color: "rgba(246,243,236,0.65)" }}>{l.out}</div>
              )}
            </div>
          );
        })}
        {lineIndex >= TERMINAL_LINES.length && <span className="cf-cursor" style={{ color: T.green }}>▍</span>}
      </div>
    </div>
  );
}

/* ================================================================
   NAV (with internal routing)
================================================================= */

const ROUTES = [
  { id: "home", label: "Home" },
  { id: "courses", label: "Courses" },
  { id: "blog", label: "Blog" },
  { id: "dashboard", label: "Dashboard" },
];

function NavBar({ route, setRoute }) {
  const [open, setOpen] = useState(false);
  return (
    <header className="sticky top-0 z-40 cf-glass-strong" style={{ borderBottom: `1px solid ${T.line}` }}>
      <div className="max-w-6xl mx-auto px-5 sm:px-8 h-16 flex items-center justify-between">
        <button
          className="flex items-center gap-2 cf-focus rounded"
          onClick={() => setRoute("home")}
        >
          <div className="w-8 h-8 rounded-md flex items-center justify-center" style={{ background: T.ink }}>
            <span className="cf-mono text-sm" style={{ color: T.green }}>{"</>"}</span>
          </div>
          <span className="cf-display font-semibold text-lg tracking-tight">Codeforge</span>
        </button>

        <nav className="hidden md:flex items-center gap-8">
          {ROUTES.map((r) => (
            <button
              key={r.id}
              onClick={() => setRoute(r.id)}
              className="cf-mono cf-tab text-[13px] cf-focus rounded pb-1"
              style={{
                color: route === r.id ? T.paper : T.slate,
                borderBottom: route === r.id ? `2px solid ${T.green}` : "2px solid transparent",
              }}
            >
              {r.label}
            </button>
          ))}
        </nav>

        <div className="hidden md:flex items-center gap-3">
          <button className="cf-focus text-sm font-medium px-4 py-2 rounded-md cf-btn-ghost">Log in</button>
          <button
            className="cf-focus text-sm font-medium px-4 py-2 rounded-md cf-btn-primary"
            onClick={() => setRoute("dashboard")}
          >
            Start learning
          </button>
        </div>

        <button className="md:hidden cf-focus" onClick={() => setOpen((o) => !o)} aria-label="Toggle menu">
          {open ? <X size={22} /> : <Menu size={22} />}
        </button>
      </div>

      {open && (
        <div className="md:hidden px-5 pb-5 flex flex-col gap-4" style={{ borderTop: `1px solid ${T.line}` }}>
          {ROUTES.map((r) => (
            <button
              key={r.id}
              onClick={() => { setRoute(r.id); setOpen(false); }}
              className="cf-mono text-sm pt-3 text-left"
              style={{ color: route === r.id ? T.paper : T.slate }}
            >
              {r.label}
            </button>
          ))}
          <div className="flex gap-3 pt-1">
            <button className="flex-1 text-sm font-medium px-4 py-2 rounded-md cf-btn-ghost">Log in</button>
            <button
              className="flex-1 text-sm font-medium px-4 py-2 rounded-md cf-btn-primary"
              onClick={() => { setRoute("dashboard"); setOpen(false); }}
            >
              Start learning
            </button>
          </div>
        </div>
      )}
    </header>
  );
}

/* ================================================================
   HOME PAGE SECTIONS
================================================================= */

function Hero({ setRoute }) {
  return (
    <section className="max-w-6xl mx-auto px-5 sm:px-8 pt-14 sm:pt-20 pb-16 sm:pb-24 grid lg:grid-cols-2 gap-12 items-center">
      <div className="cf-rise">
        <div className="cf-mono text-xs inline-flex items-center gap-2 px-3 py-1.5 rounded-full mb-6" style={{ border: `1px solid ${T.line}`, color: T.slate }}>
          <span className="w-1.5 h-1.5 rounded-full" style={{ background: T.green }} />
          // 42,000 learners shipped their first job offer
        </div>
        <h1 className="cf-display text-4xl sm:text-5xl lg:text-[3.4rem] font-semibold leading-[1.08] tracking-tight">
          Write the code.<br />Get the offer.
        </h1>
        <p className="mt-6 text-lg max-w-md" style={{ color: T.slate }}>
          Codeforge is a structured path from your first line of code to a signed
          offer letter — DSA, projects, system design, and interviews, in one track.
        </p>
        <div className="mt-8 flex flex-wrap gap-3">
          <button onClick={() => setRoute("courses")} className="cf-focus text-sm font-medium px-6 py-3 rounded-md cf-btn-primary inline-flex items-center gap-2">
            Explore courses <ChevronRight size={16} />
          </button>
          <button onClick={() => setRoute("dashboard")} className="cf-focus text-sm font-medium px-6 py-3 rounded-md cf-btn-ghost inline-flex items-center gap-2">
            <Terminal size={16} /> Try a free problem
          </button>
        </div>
        <div className="mt-10 flex items-center gap-8">
          {[["4.8/5", "avg. rating"], ["1,200+", "hiring partners"], ["87%", "placement rate"]].map(([n, l]) => (
            <div key={l}>
              <div className="cf-display text-2xl font-semibold">{n}</div>
              <div className="text-xs mt-0.5" style={{ color: T.slate }}>{l}</div>
            </div>
          ))}
        </div>
      </div>
      <div className="flex justify-center lg:justify-end">
        <TerminalHero />
      </div>
    </section>
  );
}

const CATEGORIES = [
  { id: "dsa", label: "DSA", icon: Braces },
  { id: "web", label: "Web", icon: Layers },
  { id: "mobile", label: "Mobile", icon: Smartphone },
  { id: "systems", label: "Systems", icon: Cpu },
  { id: "data", label: "Data & ML", icon: Brain },
  { id: "prep", label: "Interview Prep", icon: MessageSquare },
];

const COURSES = [
  { id: 1, cat: "dsa", icon: Braces, tag: "most popular", title: "DSA in C++", desc: "Arrays to graphs, with 400+ hand-picked problems and pattern-based recall.", meta: "16 weeks · beginner friendly" },
  { id: 2, cat: "dsa", icon: Braces, tag: "beginner friendly", title: "DSA in Java", desc: "Same proven pattern track, taught with Java syntax and collections.", meta: "16 weeks · beginner friendly" },
  { id: 3, cat: "dsa", icon: Braces, tag: "fastest growing", title: "DSA in Python", desc: "Pythonic implementations of every core pattern, from two-pointer to DP.", meta: "14 weeks · beginner friendly" },
  { id: 4, cat: "web", icon: Layers, tag: "project-based", title: "Full-Stack Web Development", desc: "React, Node, and databases — ship three production-grade apps.", meta: "20 weeks · portfolio included" },
  { id: 5, cat: "mobile", icon: Smartphone, tag: "in demand", title: "Android Development with Kotlin", desc: "Build and publish a real Android app to the Play Store.", meta: "14 weeks · project included" },
  { id: 6, cat: "mobile", icon: Smartphone, tag: "new", title: "iOS Development with Swift", desc: "SwiftUI fundamentals through to a shipped App Store submission.", meta: "14 weeks · project included" },
  { id: 7, cat: "systems", icon: Cpu, tag: "advanced", title: "System Design for Interviews", desc: "Scale a single server to millions of users, one design decision at a time.", meta: "10 weeks · for working engineers" },
  { id: 8, cat: "dsa", icon: Code2, tag: "in demand", title: "Competitive Programming", desc: "Contest-grade problem solving for ICPC, Codeforces, and onsite rounds.", meta: "12 weeks · rating-tracked" },
  { id: 9, cat: "data", icon: Brain, tag: "advanced", title: "Machine Learning Foundations", desc: "From linear regression to a deployed model, with the math made visible.", meta: "18 weeks · math refresher included" },
  { id: 10, cat: "data", icon: Database, tag: "practical", title: "SQL & Database Design", desc: "Schema design, indexing, and query optimization for real systems.", meta: "8 weeks · hands-on labs" },
  { id: 11, cat: "prep", icon: MessageSquare, tag: "quick win", title: "Aptitude & Logical Reasoning", desc: "The non-coding round that still decides who gets an interview slot.", meta: "4 weeks · self-paced" },
  { id: 12, cat: "prep", icon: MessageSquare, tag: "high impact", title: "Behavioral Interview Mastery", desc: "Structure your stories so the 'tell me about a time' round stops being scary.", meta: "3 weeks · mock-graded" },
];

function CoursesPreview({ setRoute }) {
  return (
    <section className="max-w-6xl mx-auto px-5 sm:px-8 py-16 sm:py-24">
      <div className="flex items-end justify-between mb-10 flex-wrap gap-4">
        <div>
          <div className="cf-mono text-xs mb-2" style={{ color: T.green }}>// courses</div>
          <h2 className="cf-display text-3xl sm:text-4xl font-semibold tracking-tight">Pick a track, not a playlist</h2>
        </div>
        <button onClick={() => setRoute("courses")} className="text-sm font-medium inline-flex items-center gap-1 cf-focus rounded" style={{ color: T.paper }}>
          View all {COURSES.length} courses <ArrowUpRight size={15} />
        </button>
      </div>
      <div className="grid sm:grid-cols-2 gap-5">
        {COURSES.slice(0, 4).map((c) => <CourseCard key={c.id} c={c} />)}
      </div>
    </section>
  );
}

function CourseCard({ c }) {
  return (
    <div className="cf-card rounded-xl p-6">
      <div className="flex items-start justify-between">
        <div className="w-11 h-11 rounded-lg flex items-center justify-center" style={{ background: "rgba(234,240,255,0.06)", border: `1px solid ${T.glassBorder}` }}>
          <c.icon size={20} style={{ color: T.paper }} />
        </div>
        <span className="cf-mono text-[11px] px-2 py-1 rounded-full" style={{ background: "rgba(234,240,255,0.06)", color: T.slate, border: `1px solid ${T.glassBorder}` }}>{c.tag}</span>
      </div>
      <h3 className="cf-display text-xl font-semibold mt-5">{c.title}</h3>
      <p className="text-sm mt-2" style={{ color: T.slate }}>{c.desc}</p>
      <div className="cf-mono text-[11px] mt-5 pt-4 flex items-center justify-between" style={{ borderTop: `1px solid ${T.line}`, color: T.slate }}>
        {c.meta}
        <ChevronRight size={14} />
      </div>
    </div>
  );
}

const PATH = [
  { step: "01", title: "Foundations", desc: "Syntax, logic, and your first working programs." },
  { step: "02", title: "Core DSA", desc: "The patterns behind every interview question worth asking." },
  { step: "03", title: "Build", desc: "Three shipped projects, reviewed by working engineers." },
  { step: "04", title: "Interview prep", desc: "Mock rounds, resume review, and salary negotiation." },
];

function LearningPath() {
  return (
    <section className="py-16 sm:py-24">
      <div className="max-w-6xl mx-auto px-5 sm:px-8">
        <div className="cf-mono text-xs mb-2" style={{ color: T.green }}>// the path</div>
        <h2 className="cf-display text-3xl sm:text-4xl font-semibold tracking-tight mb-12 max-w-lg">
          Four stages. One direction: forward.
        </h2>
        <div className="grid sm:grid-cols-2 lg:grid-cols-4 gap-4">
          {PATH.map((p) => (
            <div key={p.step} className="p-6 rounded-xl cf-card">
              <div className="cf-mono text-sm" style={{ color: T.green }}>{p.step}</div>
              <h3 className="cf-display text-lg font-semibold mt-4">{p.title}</h3>
              <p className="text-sm mt-2" style={{ color: "rgba(246,243,236,0.6)" }}>{p.desc}</p>
            </div>
          ))}
        </div>
      </div>
    </section>
  );
}

const FEATURES = [
  { icon: Users, title: "Mentors who ship", desc: "Every mentor is a working engineer at a product company, not a full-time instructor." },
  { icon: Trophy, title: "Outcome-tied", desc: "Course fees are structured around placement outcomes, not seat time." },
  { icon: CheckCircle2, title: "Reviewed code, always", desc: "Every project submission gets a human code review within 48 hours." },
];

function WhyUs() {
  return (
    <section className="max-w-6xl mx-auto px-5 sm:px-8 py-16 sm:py-24">
      <div className="cf-mono text-xs mb-2" style={{ color: T.green }}>// why codeforge</div>
      <h2 className="cf-display text-3xl sm:text-4xl font-semibold tracking-tight mb-12 max-w-lg">Learning to code alone is the hard way</h2>
      <div className="grid sm:grid-cols-3 gap-8">
        {FEATURES.map((f) => (
          <div key={f.title}>
            <f.icon size={22} style={{ color: T.paper }} />
            <h3 className="cf-display font-semibold text-lg mt-4">{f.title}</h3>
            <p className="text-sm mt-2" style={{ color: T.slate }}>{f.desc}</p>
          </div>
        ))}
      </div>
    </section>
  );
}

const TESTIMONIALS = [
  { name: "Ananya R.", role: "SDE-1, hired after 5 months", quote: "The DSA patterns finally clicked once I stopped memorizing solutions and started recognizing shapes." },
  { name: "Rohit K.", role: "Full-stack dev, career switcher", quote: "I went from marketing to shipping production React code in under a year." },
  { name: "Meera S.", role: "Backend engineer", quote: "Mock interviews were tougher than the real ones. That's exactly why they worked." },
];

function Testimonials() {
  return (
    <section className="py-16 sm:py-24">
      <div className="max-w-6xl mx-auto px-5 sm:px-8">
        <div className="cf-mono text-xs mb-2" style={{ color: T.green }}>// learners</div>
        <h2 className="cf-display text-3xl sm:text-4xl font-semibold tracking-tight mb-12 max-w-lg">Proof, not promises</h2>
        <div className="grid md:grid-cols-3 gap-5">
          {TESTIMONIALS.map((t) => (
            <div key={t.name} className="cf-card rounded-xl p-6">
              <div className="flex gap-0.5 mb-4">
                {Array.from({ length: 5 }).map((_, i) => <Star key={i} size={14} fill={T.amber} stroke="none" />)}
              </div>
              <p className="text-sm leading-relaxed" style={{ color: T.paper }}>&ldquo;{t.quote}&rdquo;</p>
              <div className="mt-5 pt-4" style={{ borderTop: `1px solid ${T.line}` }}>
                <div className="text-sm font-semibold">{t.name}</div>
                <div className="text-xs mt-0.5" style={{ color: T.slate }}>{t.role}</div>
              </div>
            </div>
          ))}
        </div>
      </div>
    </section>
  );
}

const PLANS = [
  { name: "Self-paced", price: "₹499", period: "/mo", features: ["All course content", "Community forum", "Progress tracking"], cta: "Start free trial" },
  { name: "Mentored", price: "₹2,999", period: "/mo", features: ["Everything in Self-paced", "Weekly 1:1 mentor calls", "Code review, 48h turnaround", "Mock interviews"], highlight: true, cta: "Start mentored track" },
  { name: "Placement", price: "₹0 upfront", period: "", features: ["Everything in Mentored", "Resume + LinkedIn overhaul", "Pay after you're hired"], cta: "Check eligibility" },
];

function Pricing() {
  return (
    <section className="max-w-6xl mx-auto px-5 sm:px-8 py-16 sm:py-24">
      <div className="cf-mono text-xs mb-2" style={{ color: T.green }}>// pricing</div>
      <h2 className="cf-display text-3xl sm:text-4xl font-semibold tracking-tight mb-12 max-w-lg">Pay for the path that fits</h2>
      <div className="grid md:grid-cols-3 gap-5">
        {PLANS.map((p) => (
          <div key={p.name} className={`rounded-xl p-6 flex flex-col ${p.highlight ? "cf-glass-strong" : "cf-card"}`} style={{ borderColor: p.highlight ? T.green : undefined }}>
            <div className="cf-display font-semibold text-lg">{p.name}</div>
            <div className="mt-4 flex items-baseline gap-1">
              <span className="cf-display text-3xl font-semibold">{p.price}</span>
              <span className="text-sm" style={{ color: T.slate }}>{p.period}</span>
            </div>
            <ul className="mt-6 space-y-3 flex-1">
              {p.features.map((f) => (
                <li key={f} className="flex items-start gap-2 text-sm">
                  <CheckCircle2 size={16} style={{ color: T.green, flexShrink: 0, marginTop: 2 }} />
                  {f}
                </li>
              ))}
            </ul>
            <button className="cf-focus mt-8 text-sm font-medium px-4 py-2.5 rounded-md" style={p.highlight ? { background: T.green, color: T.ink } : { border: `1px solid ${T.glassBorder}`, color: T.paper }}>
              {p.cta}
            </button>
          </div>
        ))}
      </div>
    </section>
  );
}

const FAQS = [
  { q: "Do I need prior coding experience?", a: "No. The Foundations stage assumes zero background and builds up from there." },
  { q: "How does the placement guarantee work?", a: "On the Placement plan, you pay a share of your first-year salary only after signing an offer — nothing upfront." },
  { q: "Can I switch tracks after enrolling?", a: "Yes, you can move between Self-paced and Mentored at any billing cycle without losing progress." },
];

function FAQ() {
  const [openIdx, setOpenIdx] = useState(0);
  return (
    <section className="py-16 sm:py-24">
      <div className="max-w-3xl mx-auto px-5 sm:px-8">
        <div className="cf-mono text-xs mb-2" style={{ color: T.green }}>// faq</div>
        <h2 className="cf-display text-3xl sm:text-4xl font-semibold tracking-tight mb-10">Questions, answered</h2>
        <div>
          {FAQS.map((f, i) => {
            const isOpen = openIdx === i;
            return (
              <div key={f.q} style={{ borderTop: `1px solid ${T.line}` }}>
                <button className="cf-focus w-full flex items-center justify-between py-5 text-left" onClick={() => setOpenIdx(isOpen ? -1 : i)}>
                  <span className="font-medium">{f.q}</span>
                  <ChevronDown size={18} style={{ transform: isOpen ? "rotate(180deg)" : "none", transition: "transform .2s ease" }} />
                </button>
                {isOpen && <p className="pb-5 text-sm" style={{ color: T.slate }}>{f.a}</p>}
              </div>
            );
          })}
          <div style={{ borderTop: `1px solid ${T.line}` }} />
        </div>
      </div>
    </section>
  );
}

function CTA({ setRoute }) {
  return (
    <section className="max-w-6xl mx-auto px-5 sm:px-8 py-16 sm:py-20">
      <div className="rounded-2xl px-8 py-14 sm:py-16 text-center cf-glass-strong">
        <h2 className="cf-display text-3xl sm:text-4xl font-semibold tracking-tight max-w-xl mx-auto">
          Your terminal is waiting for the first command
        </h2>
        <p className="mt-4 max-w-md mx-auto" style={{ color: "rgba(246,243,236,0.65)" }}>
          Start with a free problem set — no card, no commitment.
        </p>
        <button onClick={() => setRoute("dashboard")} className="cf-focus mt-8 text-sm font-medium px-7 py-3.5 rounded-md inline-flex items-center gap-2" style={{ background: T.green, color: T.ink }}>
          Start learning free <ChevronRight size={16} />
        </button>
      </div>
    </section>
  );
}

function HomePage({ setRoute }) {
  return (
    <>
      <Hero setRoute={setRoute} />
      <CoursesPreview setRoute={setRoute} />
      <LearningPath />
      <WhyUs />
      <Testimonials />
      <Pricing />
      <FAQ />
      <CTA setRoute={setRoute} />
    </>
  );
}

/* ================================================================
   COURSES PAGE (full catalog w/ category filter)
================================================================= */

function CoursesPage() {
  const [active, setActive] = useState("all");
  const filtered = active === "all" ? COURSES : COURSES.filter((c) => c.cat === active);

  return (
    <section className="max-w-6xl mx-auto px-5 sm:px-8 py-14 sm:py-20">
      <div className="cf-mono text-xs mb-2" style={{ color: T.green }}>// full catalog</div>
      <h1 className="cf-display text-3xl sm:text-4xl font-semibold tracking-tight mb-2">All courses</h1>
      <p style={{ color: T.slate }} className="mb-8 max-w-lg">
        {COURSES.length} courses across six tracks. Filter by what you're trying to become.
      </p>

      <div className="flex flex-wrap gap-2 mb-10">
        <button
          onClick={() => setActive("all")}
          className="cf-focus cf-mono text-xs px-3 py-2 rounded-full"
          style={{
            background: active === "all" ? T.green : "transparent",
            color: active === "all" ? T.ink : T.slate,
            border: `1px solid ${active === "all" ? T.green : T.line}`,
          }}
        >
          all
        </button>
        {CATEGORIES.map((c) => (
          <button
            key={c.id}
            onClick={() => setActive(c.id)}
            className="cf-focus cf-mono text-xs px-3 py-2 rounded-full inline-flex items-center gap-1.5"
            style={{
              background: active === c.id ? T.green : "transparent",
              color: active === c.id ? T.ink : T.slate,
              border: `1px solid ${active === c.id ? T.green : T.line}`,
            }}
          >
            <c.icon size={12} /> {c.label.toLowerCase()}
          </button>
        ))}
      </div>

      <div className="grid sm:grid-cols-2 lg:grid-cols-3 gap-5">
        {filtered.map((c) => <CourseCard key={c.id} c={c} />)}
      </div>
    </section>
  );
}

/* ================================================================
   BLOG PAGE
================================================================= */

const POSTS = [
  { id: 1, tag: "DSA", read: "6 min", title: "Why Brute Force First Isn't a Bad Strategy", excerpt: "The fastest path to an optimal solution usually runs straight through a working slow one." },
  { id: 2, tag: "Interviews", read: "9 min", title: "System Design Interviews: What Actually Gets Asked", excerpt: "A look at the handful of questions that show up, in disguise, across almost every onsite." },
  { id: 3, tag: "DSA", read: "5 min", title: "The Two-Pointer Pattern, Explained With Water Bottles", excerpt: "A physical metaphor for the pattern that quietly powers a third of easy-to-medium problems." },
  { id: 4, tag: "Product", read: "4 min", title: "How We Rebuilt Our Mock Interview Rubric", excerpt: "What changed after we scored 3,000 mock interviews against real hiring outcomes." },
  { id: 5, tag: "Careers", read: "8 min", title: "From Marketing to Backend: One Career-Switcher's Timeline", excerpt: "A month-by-month breakdown of a non-CS background turning into a first engineering offer." },
  { id: 6, tag: "DSA", read: "5 min", title: "Reading Time Complexity Like a Sentence", excerpt: "Big-O gets easier once you stop computing it and start reading it out loud." },
];

function BlogPage() {
  return (
    <section className="max-w-6xl mx-auto px-5 sm:px-8 py-14 sm:py-20">
      <div className="cf-mono text-xs mb-2" style={{ color: T.green }}>// blog</div>
      <h1 className="cf-display text-3xl sm:text-4xl font-semibold tracking-tight mb-2">Notes from the mentors' desk</h1>
      <p style={{ color: T.slate }} className="mb-10 max-w-lg">
        Short, practical writing on patterns, interviews, and the occasional career pivot.
      </p>
      <div className="grid sm:grid-cols-2 lg:grid-cols-3 gap-5">
        {POSTS.map((p) => (
          <article key={p.id} className="cf-card rounded-xl p-6 flex flex-col">
            <span className="cf-mono text-[11px] px-2 py-1 rounded-full self-start" style={{ background: "rgba(234,240,255,0.06)", color: T.slate, border: `1px solid ${T.glassBorder}` }}>
              {p.tag}
            </span>
            <h2 className="cf-display text-lg font-semibold mt-4 leading-snug">{p.title}</h2>
            <p className="text-sm mt-2 flex-1" style={{ color: T.slate }}>{p.excerpt}</p>
            <div className="cf-mono text-[11px] mt-5 pt-4 flex items-center justify-between" style={{ borderTop: `1px solid ${T.line}`, color: T.slate }}>
              <span className="inline-flex items-center gap-1"><Clock size={12} /> {p.read} read</span>
              <ChevronRight size={14} />
            </div>
          </article>
        ))}
      </div>
    </section>
  );
}

/* ================================================================
   DASHBOARD PAGE (mock student dashboard)
================================================================= */

const WEEKLY_ACTIVITY = [
  { day: "Mon", solved: 3 },
  { day: "Tue", solved: 5 },
  { day: "Wed", solved: 2 },
  { day: "Thu", solved: 6 },
  { day: "Fri", solved: 4 },
  { day: "Sat", solved: 7 },
  { day: "Sun", solved: 5 },
];

const ENROLLED = [
  { title: "DSA in C++", progress: 68 },
  { title: "Full-Stack Web Development", progress: 34 },
  { title: "System Design for Interviews", progress: 12 },
];

function ProgressBar({ value }) {
  return (
    <div className="w-full h-2 rounded-full" style={{ background: T.line }}>
      <div className="h-2 rounded-full" style={{ width: `${value}%`, background: T.green }} />
    </div>
  );
}

function DashboardPage() {
  return (
    <section className="max-w-6xl mx-auto px-5 sm:px-8 py-14 sm:py-20">
      <div className="flex items-end justify-between flex-wrap gap-4 mb-10">
        <div>
          <div className="cf-mono text-xs mb-2" style={{ color: T.green }}>// dashboard</div>
          <h1 className="cf-display text-3xl sm:text-4xl font-semibold tracking-tight">Welcome back, Ananya</h1>
        </div>
        <div className="cf-card rounded-xl px-5 py-3 flex items-center gap-2">
          <Flame size={18} style={{ color: T.amber }} />
          <span className="cf-display font-semibold">12-day streak</span>
        </div>
      </div>

      <div className="grid lg:grid-cols-3 gap-5 mb-5">
        <div className="lg:col-span-2 cf-card rounded-xl p-6">
          <div className="flex items-center justify-between mb-6">
            <h2 className="cf-display font-semibold text-lg inline-flex items-center gap-2">
              <TrendingUp size={18} /> Weekly activity
            </h2>
            <span className="cf-mono text-xs" style={{ color: T.slate }}>problems solved</span>
          </div>
          <div style={{ width: "100%", height: 220 }}>
            <ResponsiveContainer>
              <AreaChart data={WEEKLY_ACTIVITY} margin={{ top: 5, right: 10, left: -20, bottom: 0 }}>
                <defs>
                  <linearGradient id="cfArea" x1="0" y1="0" x2="0" y2="1">
                    <stop offset="0%" stopColor={T.green} stopOpacity={0.35} />
                    <stop offset="100%" stopColor={T.green} stopOpacity={0} />
                  </linearGradient>
                </defs>
                <CartesianGrid vertical={false} stroke={T.line} />
                <XAxis dataKey="day" tick={{ fontSize: 12, fill: T.slate }} axisLine={false} tickLine={false} />
                <YAxis tick={{ fontSize: 12, fill: T.slate }} axisLine={false} tickLine={false} allowDecimals={false} />
                <Tooltip contentStyle={{ borderRadius: 8, border: `1px solid ${T.line}`, fontFamily: "Inter" }} />
                <Area type="monotone" dataKey="solved" stroke={T.green} strokeWidth={2} fill="url(#cfArea)" />
              </AreaChart>
            </ResponsiveContainer>
          </div>
        </div>

        <div className="cf-card rounded-xl p-6">
          <h2 className="cf-display font-semibold text-lg inline-flex items-center gap-2 mb-5">
            <Calendar size={18} /> Upcoming
          </h2>
          <div className="rounded-lg p-4 cf-glass">
            <div className="cf-mono text-[11px]" style={{ color: T.slate }}>tomorrow, 6:00 PM</div>
            <div className="font-semibold mt-1">Mock interview — System Design</div>
            <div className="text-sm mt-1" style={{ color: T.slate }}>with mentor Rohit K.</div>
          </div>
          <div className="rounded-lg p-4 mt-3 cf-glass">
            <div className="cf-mono text-[11px]" style={{ color: T.slate }}>in 3 days</div>
            <div className="font-semibold mt-1">Project review — E-commerce app</div>
            <div className="text-sm mt-1" style={{ color: T.slate }}>submission due before review</div>
          </div>
        </div>
      </div>

      <div className="grid lg:grid-cols-3 gap-5">
        <div className="lg:col-span-2 cf-card rounded-xl p-6">
          <h2 className="cf-display font-semibold text-lg inline-flex items-center gap-2 mb-5">
            <BookOpen size={18} /> Enrolled courses
          </h2>
          <div className="space-y-5">
            {ENROLLED.map((c) => (
              <div key={c.title}>
                <div className="flex items-center justify-between mb-2">
                  <span className="text-sm font-medium">{c.title}</span>
                  <span className="cf-mono text-xs" style={{ color: T.slate }}>{c.progress}%</span>
                </div>
                <ProgressBar value={c.progress} />
              </div>
            ))}
          </div>
        </div>

        <div className="cf-card rounded-xl p-6">
          <h2 className="cf-display font-semibold text-lg mb-5">This week's rank</h2>
          <div className="cf-display text-4xl font-semibold" style={{ color: T.green }}>#128</div>
          <p className="text-sm mt-2" style={{ color: T.slate }}>out of 4,120 active learners on the DSA leaderboard</p>
        </div>
      </div>
    </section>
  );
}

/* ================================================================
   FOOTER
================================================================= */

function Footer({ setRoute }) {
  const cols = [
    { title: "Learn", items: ["DSA", "Web Development", "System Design", "Competitive Programming"] },
    { title: "Company", items: ["About", "Careers", "Blog", "Contact"] },
    { title: "Resources", items: ["Practice problems", "Interview guides", "Community", "Success stories"] },
  ];
  return (
    <footer style={{ borderTop: `1px solid ${T.line}` }}>
      <div className="max-w-6xl mx-auto px-5 sm:px-8 py-14 grid sm:grid-cols-2 lg:grid-cols-4 gap-10">
        <div>
          <div className="flex items-center gap-2">
            <div className="w-7 h-7 rounded-md flex items-center justify-center" style={{ background: T.ink }}>
              <span className="cf-mono text-xs" style={{ color: T.green }}>{"</>"}</span>
            </div>
            <span className="cf-display font-semibold">Codeforge</span>
          </div>
          <p className="text-sm mt-4 max-w-[220px]" style={{ color: T.slate }}>
            An independent coding education platform. Not affiliated with any other bootcamp or brand.
          </p>
        </div>
        {cols.map((c) => (
          <div key={c.title}>
            <div className="cf-mono text-xs mb-4" style={{ color: T.slate }}>{c.title}</div>
            <ul className="space-y-2.5">
              {c.items.map((i) => (
                <li key={i} className="text-sm">
                  <button onClick={() => setRoute(i === "Blog" ? "blog" : "courses")} className="cf-focus rounded">{i}</button>
                </li>
              ))}
            </ul>
          </div>
        ))}
      </div>
      <div className="max-w-6xl mx-auto px-5 sm:px-8 py-6 text-xs flex flex-wrap gap-3 justify-between" style={{ borderTop: `1px solid ${T.line}`, color: T.slate }}>
        <span>© 2026 Codeforge. All rights reserved.</span>
        <span className="cf-mono">status: all systems operational</span>
      </div>
    </footer>
  );
}

/* ================================================================
   ROOT — lightweight internal router
================================================================= */

export default function CodeforgeSite() {
  const [route, setRoute] = useState("home");

  const page = useMemo(() => {
    switch (route) {
      case "courses":
        return <CoursesPage />;
      case "blog":
        return <BlogPage />;
      case "dashboard":
        return <DashboardPage />;
      default:
        return <HomePage setRoute={setRoute} />;
    }
  }, [route]);

  return (
    <div className="cf-root min-h-screen">
      <FontLoader />
      <NavBar route={route} setRoute={setRoute} />
      {page}
      <Footer setRoute={setRoute} />
    </div>
  );
}
