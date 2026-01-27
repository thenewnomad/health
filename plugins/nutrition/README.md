# Nutrition Plugin

> **⚠️ IMPORTANT DISCLAIMER**
> **This marketplace contains nutrition tracking tools that are NOT medical advice.**
> I am not a doctor, nutritionist, or healthcare professional. These tools were created for personal use and shared for educational purposes only.
>
> **Always consult qualified healthcare providers before making significant dietary changes, especially if you have medical conditions, take medications, or have nutrient deficiencies.**

---

# Nutrition Plugin

> **⚠️ IMPORTANT: NOT MEDICAL ADVICE**
> **This plugin provides general nutritional information for educational purposes only.**
> I am not a doctor, nutritionist, or healthcare professional. This tool was created for personal use and shared publicly for educational purposes.
>
> **This should not replace professional medical advice, diagnosis, or treatment. Always consult qualified healthcare providers before making significant dietary changes, especially if you have medical conditions, take medications, or have nutrient deficiencies.**

---

A Claude Code plugin providing personalized nutrition guidance and tracking for women in perimenopause.

## What It Does

This plugin helps you:
- Create personalized nutrition profiles tracking symptoms, goals, and dietary restrictions
- Log daily meals with comprehensive micronutrient tracking (protein, iron, calcium, magnesium, B vitamins, vitamin D, omega-3s, fiber)
- Get evidence-based recommendations for hormone balance, bone health, iron absorption, metabolism, and energy
- Receive symptom-specific nutrition guidance (hot flashes, sleep issues, fatigue, mood changes, bone health)

## Installation

### Prerequisites

1. Install Claude Code: https://code.claude.com
2. Have the plugin marketplace added (see main [README](../../README.md))

### Install This Plugin

```bash
# Add the marketplace
/plugin marketplace add https://github.com/thenewnomad/health

# Install the plugin
/plugin install nutrition@health
```

## Getting Started

### 1. Initial Setup

In Claude Code, say:
```
I want to set up my perimenopause nutrition tracking.
```

Or use the skill directly:
```
/peri-nutrition
```

### 2. Create Your Profile

Claude will guide you through a conversational Q&A to create your personalized profile:
- Age and perimenopause stage
- Current symptoms (hot flashes, sleep issues, fatigue, mood changes, etc.)
- Dietary preferences and restrictions
- Health goals

### 3. Start Tracking

Log meals naturally:
```
I had scrambled eggs with spinach and avocado for breakfast.
```

Get instant feedback on:
- Protein, iron, calcium, magnesium, B vitamins, vitamin D
- How the meal supports your symptoms
- Suggestions for optimizing nutrition

### 4. Get Personalized Recommendations

Ask questions like:
```
What foods help with hot flashes?
What should I eat for better sleep?
How can I boost my iron absorption?
What are good calcium sources for bone health?
```

## Files Created

The plugin creates a `peri-nutrition-logs/` directory in your project with:
- `profile.md` - Your personalized health profile (symptoms, goals, dietary info)
- `tracking.md` - Daily nutrition logs with meal entries and nutrient tracking

**Privacy Note:** All data is stored locally on your machine. Nothing is sent to external servers. The `.gitignore` file prevents these logs from being committed to version control.

## Features

### Comprehensive Tracking
- **Macronutrients:** Protein, carbs, fats
- **Key Micronutrients:** Iron, calcium, magnesium, B vitamins (B6, B12, folate), vitamin D, omega-3s
- **Fiber:** For digestive health and blood sugar regulation

### Symptom-Specific Guidance
- **Hot Flashes:** Phytoestrogens, omega-3s, vitamin E
- **Sleep Issues:** Magnesium, tryptophan, complex carbs
- **Fatigue:** Iron, B12, steady blood sugar
- **Mood Changes:** Omega-3s, B vitamins, magnesium
- **Bone Health:** Calcium, vitamin D, magnesium, vitamin K

### Evidence-Based Recommendations
- Hormone balance through nutrition
- Iron absorption optimization (heme vs non-heme, vitamin C pairing)
- Metabolism support (protein distribution, fiber, hydration)
- Anti-inflammatory eating patterns

### Dietary Inclusive
- Vegetarian and vegan options
- Pescatarian recommendations
- Cultural dietary considerations
- Allergy and restriction-aware

## What This Plugin Is NOT

❌ Medical advice or healthcare services
❌ Created by medical professionals
❌ Intended to diagnose, treat, or cure any condition
❌ A replacement for professional nutrition counseling or medical care
❌ Suitable for people with eating disorders or complex medical needs

## What This Plugin IS

✅ An educational nutrition tracking tool
✅ Created for personal use and shared publicly
✅ Based on general perimenopause nutrition research
✅ Privacy-focused (all data stored locally)
✅ Open source and free to use (MIT License)
✅ A supplement to professional healthcare, not a replacement

## Support

- **Questions about the plugin:** Open an issue on GitHub
- **Health concerns:** Always consult your healthcare provider
- **Feature requests:** Contributions welcome (see [CONTRIBUTING.md](../../CONTRIBUTING.md))

## License

MIT License - see [LICENSE](./LICENSE) file

This plugin comes with NO WARRANTY and is provided "as is" for educational purposes only.

## Acknowledgments

This plugin is based on general perimenopause nutrition research and evidence-based dietary recommendations. It is not a substitute for personalized medical advice from qualified healthcare professionals.

