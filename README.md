# SAGAR
import React from "react";
<div className="absolute bottom-6 left-6 bg-white/90 backdrop-blur px-4 py-2 rounded-2xl shadow-md">
<p className="font-semibold text-emerald-700">Plastic‑Free Choices</p>
<p className="text-xs text-slate-600">Join the movement 🌍</p>
</div>
</div>
</motion.div>
</div>
</section>


{/* Unique Feature Grid */}
<section id="about" className="relative py-20 bg-gradient-to-r from-emerald-100 to-white">
<div className="mx-auto max-w-7xl px-6 grid md:grid-cols-3 gap-10">
{["Curated for Impact", "Carbon Neutral Delivery", "Trusted Quality"].map((title, i) => (
<motion.div
key={i}
initial="hidden"
whileInView="show"
viewport={{ once: true }}
variants={fadeIn}
className="rounded-3xl bg-white p-8 shadow-lg hover:shadow-xl border border-emerald-200"
>
<h3 className="text-xl font-bold text-emerald-700">{title}</h3>
<p className="mt-3 text-slate-600 text-sm">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Eco‑friendly details that matter.
</p>
</motion.div>
))}
</div>
</section>


{/* Impact Banner */}
<section id="impact" className="relative py-20">
<div className="mx-auto max-w-6xl px-6 rounded-[3rem] bg-emerald-600 text-white shadow-xl p-12 text-center">
<h2 className="text-3xl md:text-4xl font-extrabold">Together, We Create Change</h2>
<p className="mt-3 max-w-2xl mx-auto text-emerald-50">
Every purchase contributes to climate projects and ocean cleanups. Small steps, big difference.
</p>
<div className="mt-8 grid grid-cols-1 sm:grid-cols-3 gap-6">
{[{ value: "200k+", label: "kg CO₂ offset" }, { value: "95k+", label: "Items saved from landfill" }, { value: "1.5M+", label: "Plastic bottles removed" }].map((s, i) => (
<div key={i} className="bg-white/10 backdrop-blur p-6 rounded-2xl">
<p className="text-3xl font-bold">{s.value}</p>
<p className="text-sm opacity-90">{s.label}</p>
</div>
))}
</div>
</div>
</section>


{/* Footer */}
<footer id="contact" className="bg-emerald-700 text-white py-12">
<div className="mx-auto max-w-7xl px-6 text-center">
<h3 className="text-2xl font-bold">Stay Connected</h3>
<p className="mt-2 text-emerald-50">Subscribe for eco tips and new arrivals.</p>
<form className="mt-5 flex max-w-md mx-auto bg-white rounded-full overflow-hidden">
<input type="email" placeholder="Your email" className="flex-1 px-4 py-3 outline-none text-slate-800" />
<button className="bg-emerald-600 px-6 py-3 font-semibold">Join</button>
</form>
<p className="mt-6 text-xs text-emerald-100">© {new Date().getFullYear()} EcoFinds. Built with 🌱 for a greener world.</p>
</div>
</footer>
</div>
);
}
