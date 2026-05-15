# Rodrino
Flair

## Flair bartender prompt example (with logo)
Below is an image-generation prompt example for an ultra-realistic flair bartender scene. The shirt bears the embroidered logo "100xtressbar" on the left chest and a small matching logo on the upper back.

**Prompt (English, copy-paste):**

"Ultra-realistic flair bartender in a luxurious speakeasy bar with warm amber lighting and golden reflections on a polished wooden bar, light atmospheric smoke and airborne particles. Cinematic slow-motion tracking shot: the bartender adjusts the sleeves of an elegant black shirt, wearing suspenders and thin leather gloves. The black shirt clearly displays an embroidered logo reading '100xtressbar' on the left chest (subtle embroidered texture, white/gold thread), with a small matching logo printed on the upper back. Premium bottles glow in the blurred background. The bartender tosses a metallic cocktail shaker into the air and performs a perfect behind-the-back catch, captured mid-spin. Anamorphic 35mm lens, shallow depth of field, cinematic bokeh, volumetric lighting, natural reflections on metal, ultra-detailed skin pores and realistic metal highlights, soft film grain, dramatic yet warm Hollywood color grading, 8K ultra-detailed, hyperreal textures, intense luxurious atmosphere, filmic composition."

**Negative prompt:**

"text, watermark, logo unrelated, extra logos, signature, lowres, blurry, deformed hands, extra fingers, cartoon, anime, oversaturated colors, noisy, artifacts, overexposed, underexposed, flat lighting, unrealistic proportions"

**Suggested settings**

- MidJourney (example): `--ar 16:9 --v 5 --q 2 --stylize 250` (append to end of prompt)
- Stable Diffusion / SDXL:
  - Resolution: 2048x1152 or 3072x1728 (16:9)
  - Steps: 30–60
  - Sampler: Euler a / DPM++ 2M Karras
  - CFG/Guidance scale: 7.0–9.0
  - Denoising: default

**Tips**
- Specify "embroidered texture" and thread color (white or gold) to keep the logo realistic and readable.
- If the model hallucinates the text, try using an image reference of the logo with img2img/inpainting or add "use reference logo image" when supported.
- For trademark/brand accuracy, provide a high-res logo image for inpainting or refer to a URL of the actual logo.

---

If you'd like, I can adapt this prompt for a specific generator (MidJourney v6, SDXL checkpoint, Leonardo.ai, etc.), translate it to Portuguese, or create a short caption/title version. Just tell me which option you prefer.