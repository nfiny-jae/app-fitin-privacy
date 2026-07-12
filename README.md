# FitIn Privacy Policy

**Effective date:** 9 July 2026  
**App:** FitIn (`com.nfiny.fitin`)  
**Developer:** nfiny-jae

FitIn is a fitness accountability app. This policy explains what information we collect, how we use it, and the choices you have.

## Summary

- We collect only what we need to run the app: account details, fitness logs, optional profile info, and (if you enable them) location and push notifications.
- We do **not** sell your personal information.
- We do **not** show ads or use third-party analytics trackers.
- You can delete your account in the app or by email — see our [Account & Data Deletion](account-deletion.md) page for full steps.

## Information we collect

### Account information

When you sign in, we receive information from your chosen provider:

- **Google Sign-In:** email address, display name, and a unique Google account identifier.
- **Sign in with Apple (iOS):** email address (on first sign-in), display name (if you provide it), and a unique Apple account identifier.

We store your email, name, and provider identifier to create and maintain your FitIn account.

### Profile and preferences

If you complete onboarding or update your profile, we may store:

- Preferred units (kg/lb)
- Sex, age, height, fitness goal, and experience level (all optional)
- Home gym name and coordinates (optional — set via device location or manual pin)
- Avatar choice (emoji or uploaded photo)
- Starter strength benchmarks (optional)

### Fitness and activity data

To provide workout tracking, progress charts, achievements, and social features, we store:

- Workout sessions (start/end times, target muscle groups)
- Individual sets (exercise, weight, reps, duration, distance, effort, personal-record flags)
- Body metrics (body weight, resting heart rate)
- Gym check-ins and check-outs
- Experience points, levels, streaks, and achievement unlocks
- Social feed events visible to members of your workout groups

### Social features

If you use workout groups, we store:

- Group memberships and roles
- Your display name and avatar as shown to other group members
- Block and report records (blocks are one-directional and silent; reports are stored for review)

We do **not** expose your email address to other users.

### Device and technical data

- **Push notification tokens** — if you allow notifications, we store an Expo push token so we can send workout reminders and group activity alerts.
- **Authentication tokens** — access and refresh tokens are stored securely on your device (not in plain local storage).
- **Offline workout queue** — if you log workouts while offline, pending changes are stored locally on your device until they sync.

### Information we do not collect

- We do not collect payment or billing information (FitIn is free).
- We do not use third-party advertising or analytics SDKs.
- Biometric unlock (Face ID / fingerprint), when enabled, is handled entirely on your device and is not sent to our servers.

## How we use your information

We use the information above to:

- Authenticate you and keep you signed in
- Store and display your workouts, progress, and achievements
- Power workout groups, leaderboards, feeds, and presence features
- Send push notifications you have opted into
- Operate, secure, and improve the FitIn service
- Respond to support requests and enforce our community guidelines (e.g. reviewing reports)

## How we share your information

We do **not** sell your personal information.

We share limited data only as needed to run the app:

| Third party | Purpose |
|---|---|
| **Google** | Sign-in authentication |
| **Apple** | Sign-in authentication (iOS) |
| **Render** | Hosts the FitIn API |
| **PostgreSQL database provider** | Stores app data |
| **Object storage provider** | Stores optional profile photos |
| **Expo** | Delivers push notifications and over-the-air app updates |

Within FitIn, other members of a workout group you belong to can see your display name, avatar, workout activity shared to the group feed, leaderboard entries, and presence status (e.g. checked in at the gym). They cannot see your email address.

We may also disclose information if required by law or to protect the rights, safety, and security of FitIn and its users.

## Data retention

We keep your data for as long as your account is active. If you deactivate your account, we retain your data so you can reactivate by signing in again. If you delete your account permanently, we remove your personal data promptly — see [Account & Data Deletion](account-deletion.md) for what is deleted, what may be kept, and retention periods.

## Data security

We use industry-standard measures to protect data in transit (HTTPS) and at rest. Authentication tokens are hashed on the server; refresh tokens are rotated on use. No method of transmission or storage is 100% secure, but we work to safeguard your information.

## Your choices and rights

Depending on where you live, you may have rights to access, correct, export, or delete your personal information.

You can:

- **Update profile information** in the FitIn app at any time
- **Turn off push notifications** in your device settings
- **Revoke location access** in your device settings (home gym pinning and location-based features will stop working)
- **Sign out** of FitIn at any time from your profile screen
- **Deactivate your account** temporarily from your profile screen (hides your account; sign in again to reactivate)
- **Delete your account** permanently from your profile screen (removes your personal data from our systems) — see [Account & Data Deletion](account-deletion.md)
- **Contact us** for data access or other privacy requests (see below)

Use of FitIn is also governed by our [Terms of Service](https://github.com/nfiny-jae/app-fitin-tos).

## Children's privacy

FitIn is not directed at children under 13, and we do not knowingly collect personal information from children under 13. If you believe a child has provided us with personal information, please contact us and we will delete it.

## International users

FitIn is operated from Australia. If you use the app from outside Australia, your information may be processed in Australia and in the countries where our service providers operate (including the United States).

## Changes to this policy

We may update this policy from time to time. We will post the revised version in this repository and update the effective date above. Continued use of FitIn after changes take effect means you accept the updated policy.

## Contact

For privacy questions or data access requests, email **dev@nfiny.com**. Please include the email address associated with your FitIn account so we can verify your request.

To delete your account and associated data, follow the steps on our [Account & Data Deletion](account-deletion.md) page.
