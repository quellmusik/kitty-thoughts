# Sogni Platform Report — what it actually does, and what it costs

**Scouted live:** Sun Nov 1, 2026, signed in at app.sogni.ai as @samusw. Research only — generations were staged to read their quoted cost, then backed out. **No Spark was spent.** Costs are UI quotes at the time of reading (Sogni's Spark estimates are dynamic and can drift within minutes) or public list prices. UI rate: **1 Spark = $0.005**. Account balance at scout time: **1,441.64 Spark total** (1,370.13 settled). Sensitive Content Filter verified **OFF** on the account.

---

## Bottom line (Kitty's recommendations)

1. **ACE-Step is the steal of the platform.** A full 5-minute song on ACE-Step 1.5 XL Turbo costs ~**10.8 Spark (≈5¢)**. That's a real third lane for the Suno-vs-ElevenLabs keep-one decision (due ~Nov 17–18) — test it before deciding. MiniMax Music 3 is the quality lane at ~24× the price per minute (~51 Spark/min).
2. **Uncensored Seedance is real — and priced like it.** Sweet spot: **5 sec at 720p = 346.68 Premium Spark (~$1.73)**. A 30-sec 1080p clip runs **5,118 Spark (~$25.59)** — more than 3× the current balance. Premium Spark only; the Unlimited subscription does **not** cover it.
3. **Best-value video overall is LTX 2.5** (~9.2 Spark/sec at 1080p-class, not Premium-locked) and **Wan 3 Uncensored** (16 Spark/sec at 480p) for longer uncensored clips.
4. **Skip the Unlimited subscription.** It excludes the premium partner models (Seedance, GPT Image) that matter most, and the account's standing rule is pay-as-you-go anyway. The monthly free boost (400 Spark) plus cheap packs cover real usage.
5. **Personas is worth a look** — Sogni's built-in character library (portrait/sheet + ~15s voice sample, reusable across projects). Noted here as a platform capability only.
6. Windows is still waitlist-only — on the Dell, the **web Create app** is the front door; **Sogni Pocket (iOS)** is the full app on the phone.

---

## ⭐ Seedance spotlight (ByteDance video)

Sogni's UI never says "NSFW" — it says **"Uncensored"**, "(18+)", "more permissive content policy", "mature themes". The public page also calls the uncensored build **"Seedance 2.5 Spicy"**.

- **Variants in-app:** standard 2.5 / 2.0 Mini / 2.0 4K, plus a separate uncensored group: **2.5 Uncensored** and **2.0 Mini Uncensored** (no 4K uncensored). Model IDs: `seedance-2-5`, `seedance-2-5-uncensored`. Creator: ByteDance Seed, served via BytePlus ModelArk. Standard builds are vendor-moderated ("Sogni cannot switch that off"); that banner disappears on the uncensored variants.
- **Specs:** 4–30 sec clips, 24 fps, native audio, up to 1080p (480p/720p/1080p; portrait 9:16 supported). **Image-to-Video supports start AND end frames** (2.5/4K only). Reference-to-Video: up to 30 images / 10 videos / 10 audio.
- **Pricing — Seedance 2.5 Uncensored, per second / 5 sec / 30 sec (Spark):**

| Res | per sec | 5 sec | 30 sec |
|---|---|---|---|
| 480p | 30.84 | 154.20 | 925.20 |
| 720p | 69.34 | **346.68** | 2,080.08 |
| 1080p | 170.59 | 852.93 | 5,117.58 |

  Standard 2.5 is ~15% cheaper (5 sec: 134 / 300 / 739 Spark). Image-to-Video 5 sec 720p: 2.5 Uncensored 346.68; 2.0 Mini Uncensored 189.00; standard 2.0 Mini 98.28. Premium Spark only; subscribers save 5–10%.
- **Gate:** a one-time likeness & consent agreement is required for real people (the scout did **not** accept it; fictional characters unaffected). Unaccepted accounts get error 4103, nothing charged.

## Images

~200 models in the picker. Categories: Next-Gen Diffusion (Krea 2 Turbo, Chroma, FLUX [schnell], Qwen Image, Z-Image, Dark Beast, MOSS-Image, Chroma Flash), Image Editing (FLUX 3 Klein, Krea 2 Identity Edit, GPT Image, **Seedream 5.0 Pro Uncensored**, Qwen Image Edit), ~40 SDXL models (Juggernaut XL, CyberRealistic XL, RealVisXL…), ~40 SD1.5-era, ~20 Turbo/Lightning, 10 LCM, SD3. Sogni advertises **"50+ uncensored community fine-tunes — Dark Beast, Chroma1-HD, and more — available with the filter off."**

- Controls: batch 1/4/9/16, sizes to ~4.2MP (GPT Image ~8MP), **Guide Image** support, **LoRA support ("Browse LoRAs")**, styles, seed lock, samplers/schedulers/VAE selection, JPG/PNG/WebP. **No negative-prompt field was found** in any panel opened.
- GPT Image panel is different: up to 16 reference images, edit mask, quality tiers to "Maximum", transparent background. Vendor-moderated, Premium Spark only; 2.84 Spark for a 1024×1536 HQ image.
- Sampled costs (dynamic, treat as snapshots): FLUX.1 [schnell] 0.77–2.43 Spark/img; Krea 2 Turbo 2.43; Chroma1-HD actual charged history: 1.61–2.79 per single, 9.46 per 4-batch; Juggernaut XL ~2.2–2.3 per 2-batch.

## Video (other models)

Shared: AI Screenwriter on by default, batch 1/2/4/8, native audio toggles, seed control. All except LTX and MiniMax H3 were Premium-Spark-only as observed.

| Model | Notes | Staged cost |
|---|---|---|
| **MiniMax H3** | Open-weights, native stereo audio; Text/Image/Reference/Extend/Sound-to-Video; 2K, ≤15s | 6s Balanced ≈ 58.75 Spark; FastH3 23.50 |
| **LTX 2.5** (Lightricks) | 4K, ≤20s, up to 60fps, synced dialogue/foley | 5s 1080p-class Turbo ≈ 46.10 Spark (~9.2/s) |
| **Wan 3 Uncensored** | 1080p, 2–30s, 30fps, optional audio | 12s @480p = 192 Spark (16/s) |
| **HappyHorse 1.1** (Alibaba) | Talking/lip-sync characters; vendor-moderated | 5s 1080p = 234 Spark (~46.8/s) |
| **FlashVSR 1.1** | Video upscale to 1080p/1440p, keeps audio/timing | unverified (needs an upload) |

## Music & speech

Two Text-to-Music workflows, 3 models. Shared: style prompt (required), batch 1/4/8/16, duration slider, lyrics toggle with built-in template + AI Songwriter + multilingual support, output MP3/WAV/FLAC. Lyrics OFF = instrumental (no separate instrumental toggle, no seed control seen).

| Model | Max length | Cost |
|---|---|---|
| **ACE-Step 1.5** (MIT, GitHub) | **10 min** | Turbo 60s = 1.85 Spark; 600s = 18.54 |
| **ACE-Step 1.5 XL** | 5 min | Turbo 60s = 2.16; 300s = 10.78; SFT 60s = 12.17 |
| **MiniMax Music 3** (Aug 2026, open-weight) | 5 min | 60s = 50.98 Spark; 300s = 254.92 |

ACE-Step extras: Turbo vs SFT (experimental, guidance control) modes, musical parameters — tempo, time signature, key. MiniMax: steps fixed at 30, no musical parameters.

**Speech (TTS):** 9 studio voices (English: Serena, Ryan, Aiden, Eric, Dylan + Chinese/Japanese/Korean voices), voice cloning and voice design offered, 10 languages, ~14.38 Spark for a short 54-character clip. Underlying model name not shown in-app (unverified).

## Editing & tools

- **Upscale Image** (RTX VSR): 2×/4×/8K/16K outputs (higher tiers need Premium Spark/SOGNI/Unlimited). **Remove Background** (BiRefNet): transparent PNG or mask. **Cut Out an Object** (SAM 3), **Image to 3D** (Pixal3D) — pages not opened, details unverified.
- **Upscale Video** (FlashVSR), **Clip Mixer** (built-in timeline editor; MP4/MOV/WebM/PNG/JPG), **Extend Video**, **Motion Transfer**, **Replace Subject**, **Sound to Video**.
- **Personas:** character library — upload a portrait/character sheet + ~15s voice sample; reusable across Sogni App and Sogni Chat; private to the account. This account has none yet.
- **API:** one Sogni API key reaches the whole catalog (incl. `seedance-2-5-uncensored`); a "Creative Agent Skill" lets an external agent call Sogni generation as tools.

## The Super Apps layer (sogni.ai/super-apps)

- **Sogni Studio** (Mac, Apple silicon) — local + Supernet generation, 200+ models, worker mode to earn from idle compute. **Sogni Create** (web/Android) — the main app. **Sogni Pocket** (iOS 17+, iPhone 13 Pro+) — full power incl. on-device generation.
- **Photobooth** (AI portraits of yourself), **Worlds** (interactive AI adventures), **Chat** (agent workspace), **Restore** (old-photo repair), **360** (seamless 360° scenes), **Makeover**, **Sticker Bot** (Telegram/Discord), **Ink** (tattoo concepts), **Infinity** (seamless tessellations), **Vibe** (idea → image batches → animated video). Windows/Linux: waitlist only.

## Account & platform

- **Premium Spark packs** (never expire; required for third-party/premium models): 250/$1.99 · 550/$3.99 · **1,000/$6.99** (Sam's pack) · 2,000/$12.99 · 4,500/$26.99 (most popular) · 10,000/$55.99 · 20,000/$105.99. Auto top-up exists (buys 4,500 when balance <500; $60/day, $300/mo caps) — **not enabled**.
- **Unlimited:** from $20/mo, Unlimited Pro from $50/mo, 3-day trial, USDC accepted. Fair-use unlimited on covered models — but **premium partner models are billed in Spark on every plan**, so Seedance/GPT Image are never "free" under it. Subscribers get 5%/10% off Spark renders.
- **Free Spark:** Monthly Boost **400 Spark** (claimed; next in ~29 days) — there is **no daily** free-points mechanism. Email verification paid 25; Etherlink welcome 100 (claimed). Share & Earn referral program exists.
- **Settings verified:** Sensitive Content Filter OFF; "blur mature content (R+)" ON (display blur only); prompts/settings saving ON (encrypted).

## Unverified / not checked

Per-model costs for the ~130 long-tail image models; audio download button on finished tracks; upscale/remove-background prices (need a file upload); Speech's underlying model; Usage page; full Pricing and Refund policies; complete commercial terms text (beyond the likeness-agreement and vendor-moderation notes above); Cut Out / Image-to-3D tool pages.

*Method: in-app staging reads + Sogni's public model/pricing pages + Sam's wallet history for actual charged prices. Nothing was generated, purchased, or agreed to during the scout.*
