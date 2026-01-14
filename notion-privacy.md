# Privacy Policy

**Last Updated:** January 2026

## Introduction

Save to Notion ("the Extension") is a Chrome browser extension that allows you to save web content to your Notion databases. This privacy policy explains how we handle your data.

## Data Collection

### Data We Collect

The Extension collects the following information:

1. **Page Metadata**: When you use the Extension, it extracts metadata from the current web page, including:
   - Page title
   - URL
   - Description
   - Images
   - Author information
   - Publication date
   - Site name and favicon

2. **Authentication Data**: When you connect your Notion account:
   - OAuth access tokens
   - Workspace information (ID, name, icon)
   - User information (ID, email, name, avatar URL)

3. **Form Configurations**: Custom form settings and database preferences you configure within the Extension

4. **Settings**: Your Extension preferences and settings

### How We Collect Data

- **Page Metadata**: Extracted directly from the web page you are viewing using content scripts
- **Authentication Data**: Obtained through Notion's OAuth 2.0 authentication flow
- **Form Configurations and Settings**: Stored locally when you configure the Extension

## Data Storage

All data collected by the Extension is stored **locally on your device** using Chrome's local storage API. This includes:

- Authentication tokens
- Workspace and user information
- Form configurations
- Cached database lists
- Extension settings

**We do not transmit, store, or have access to any of this data on our servers.**

## Data Usage

The Extension uses collected data for the following purposes:

1. **Saving Content to Notion**: Page metadata and any additional information you provide is sent directly to Notion's API to create pages in your databases
2. **Authentication**: OAuth tokens are used to authenticate API requests to Notion on your behalf
3. **Functionality**: Form configurations and settings are used to customize your experience within the Extension

## Third-Party Services

### Notion API

The Extension integrates with Notion's API to:
- Authenticate your account via OAuth 2.0
- Create pages in your Notion databases
- Retrieve information about your workspaces and databases

All data sent to Notion is subject to [Notion's Privacy Policy](https://www.notion.so/Privacy-Policy-3468d120cf614d4c9014c09f6bfc55dc). We recommend reviewing their privacy policy to understand how they handle your data.

## Data Sharing

**We do not share, sell, or transmit any of your data to third parties** except:

- Data you explicitly choose to save is sent to Notion's API (as described above)
- Data stored locally in Chrome's local storage (which is subject to Chrome's privacy policies)

## Your Rights

You have the following rights regarding your data:

1. **Access**: All data is stored locally on your device and can be accessed through Chrome's storage
2. **Deletion**: You can disconnect your Notion account at any time, which will clear all authentication data. You can also uninstall the Extension to remove all stored data
3. **Control**: You control what content is saved to Notion - the Extension only saves data when you explicitly choose to do so

## Security

- All authentication is handled through Notion's secure OAuth 2.0 flow
- Access tokens are stored locally in Chrome's secure storage
- All API communications with Notion are encrypted using HTTPS

## Permissions

The Extension requires the following permissions:

- **Storage**: To save your settings and form configurations locally
- **Active Tab**: To extract metadata from the current web page
- **Identity**: To authenticate with Notion via OAuth
- **Context Menus**: To provide right-click menu options
- **Host Permission (api.notion.com)**: To communicate with Notion's API

## Changes to This Policy

We may update this privacy policy from time to time. The "Last Updated" date at the top of this policy indicates when it was last revised.

## Contact

If you have questions about this privacy policy or how the Extension handles your data, please contact us through the Extension's support channels.

## Compliance

This Extension is designed to comply with applicable privacy laws and regulations. By using the Extension, you acknowledge that you have read and understood this privacy policy.
