<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Transform field operations from chaos to precision"
	subtitle="Stop wasting 2-3 hours daily on inefficient routing. Our intelligent platform combines route optimization with real-time GPS validation, turning guesswork into precise execution for field service teams."
	imageSrc="/generated/image-candid-documentary-style-photograph-of-a.webp"
	centered={false}
/>
<LogoScroller
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/fedex.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/ups.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/dhl.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/usps.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Built for field operations that need more than just Google Maps"
	text="RouteWise combines web-based planning, mobile execution, and GPS tracking into one connected platform. Field service managers at mid-size companies use our intelligent route optimization to eliminate 2-3 hours of daily waste from inefficient routing. Plan, dispatch, and confirm every job with real-time visibility—from the first route to the final stop."
/>

<Testimonials
	testimonials={[
		{
			name: "Maria Gonzalez",
			position: "Field Service Manager",
			company: "ProTech Solutions",
			quote:
				"We cut our daily route planning from 45 minutes to just 8 minutes. The GPS validation eliminated customer disputes about missed appointments, and our team completed 23% more service calls per day.",
			image: "/generated/image-natural-light-corporate-headshot-portrai.webp"
		},
		{
			name: "Marcus Williams",
			position: "Operations Director",
			company: "Midwest Delivery Co",
			quote:
				"Real-time tracking reduced our fuel costs by $28,000 annually and eliminated overtime from inefficient routing. Our drivers love the mobile app - it's simple and actually saves them time on the road.",
			image: "/generated/image-professional-headshot-of-a-confident-afr.webp"
		},
		{
			name: "Linda Chen",
			position: "Fleet Coordinator",
			company: "Summit Logistics",
			quote:
				"The integrated platform gave us complete visibility into our 50-vehicle fleet. We reduced customer complaints by 67% and increased on-time deliveries from 78% to 94% in just three months.",
			image: "/generated/image-professional-headshot-of-an-african-amer.webp"
		}
	]}
/>

<Features
	title="Turn chaos into precision"
	subtitle="Everything you need to optimize field operations and eliminate routing inefficiencies"
	features={[
		{
			title: "Intelligent route optimization",
			description: "Cut 2-3 hours of daily inefficiency with AI-powered routing that adapts to real-time traffic, customer priorities, and technician skills."
		},
		{
			title: "Real-time GPS validation",
			description: "Know exactly where your team is and when jobs are completed with automated GPS tracking that provides instant proof of service delivery."
		},
		{
			title: "Complete execution visibility",
			description: "Bridge the gap between planning and reality with live updates that show route progress, delays, and completion status across your entire fleet."
		},
		{
			title: "Multi-device synchronization",
			description: "Plan routes on web, execute on mobile, and track with GPS hardware—all synchronized instantly across your entire operation."
		},
		{
			title: "Driver-friendly mobile app",
			description: "Reduce driver resistance with an intuitive mobile interface that makes route following simple while automatically documenting job completion."
		},
		{
			title: "Performance analytics dashboard",
			description: "Transform route data into actionable insights with detailed analytics that identify efficiency opportunities and measure team performance improvements."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction
	title="Put every route on autopilot"
	subtitle="Stop wasting hours. Start seeing results."
	description="From first stop to final proof of delivery, RouteWise keeps your day running smoothly—without the guesswork, delays, or driver pushback."
	imageSrc="/generated/image-happy-field-service-manager-black-woman-.webp"
	callsToAction={[
		{
			href: "/",
			label: "Start saving hours with a free trial",
			variant: "primary"
		},
		{
			href: "/",
			label: "Book demo",
			variant: "secondary"
		}
	]}
/>
