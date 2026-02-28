# Prompts Overview

nBlick’s **prompts system** gives you a flexible way to manage how text inputs are transformed into AI-driven outputs. Prompt templates control the instructions given to the model and can be customized, toggled on/off, or automatically created.

> 💡 Prompts are a powerful mechanism for shaping output behavior. In nBlick, they are reusable, adjustable patterns that influence how models interpret and process text.

## Prompt Concepts

### What Is a Prompt?

A *prompt* in nBlick is a reusable instruction set fed to the model at execution time. It defines how input is framed, what role the model takes, and how the output should be structured.

Each prompt consists of:

- A **name** for identification
- A **template** with placeholders for dynamic data
- Settings controlling its use within workflows

## Prompt Management

Prompt management in nBlick focuses on creating, modifying, and controlling whether prompts participate in automated processes.

## Automatic Prompt Generation

nBlick can generate prompts for you automatically based on selected patterns and templates. This helps accelerate setup and ensures consistency.

### How It Works

- When creating a new metric or pipeline, the system suggests a prompt based on context.
- These suggestions can be accepted as-is or modified to better suit your needs.
  
Automatic generation is designed to:

- Save time
- Reduce manual effort
- Provide solid starting points for customization

## Editing Existing Prompts

After prompts are created — whether manually or through automation — you can update them at any time.

### Editable Fields

- **Label/Name:** The visible identifier for the prompt
- **Template Content:** The text with dynamic placeholders
- **Metadata:** Tags, descriptions, or grouping information

Editing ensures that your prompts evolve with your workflows and output goals.

## Enabling and Disabling Prompts

You don’t always need every prompt to be active. nBlick lets you **enable** or **disable** prompts without deleting them.

### Toggle Prompt Status

| Action | Description |
|--------|-------------|
| **Enable** | Makes the prompt available to pipelines and automated use cases |
| **Disable** | Prevents the prompt from triggering in workflows, but keeps it stored |

This lets you manage prompt availability without losing historical configurations.

## Prompt Lifecycle

1. **Creation**
   - Automatically by nBlick
   - Manually by users
2. **Modification**
   - Edit name/template
   - Adjust placeholders
3. **Activation / Deactivation**
   - Enable for use
   - Disable as needed
4. **Reuse**
   - Across multiple workflows
   - In different pipelines

## Best Practices

- Comment prompts with context to make their purpose easy to understand
- Keep templates DRY (Don’t Repeat Yourself) by using common variables
